---
layout: default
title: FAQ
parent: DASH
grand_parent: Products
nav_order: 
published: false

---
# Export DASH

Export Items or entire DASHES to different file formats such as PDF or Excel. Choose the E-Mail As… option to attach directly in an E-Mail.

* Export Items or Entire DASH
  * Export individual DASH Items by clicking on the Export icon located in the Item’s Tools and Indicators section; Export the Entire DASH by clicking on the same Export icon located in the upper right corner of the DASH
* To PDF/Image
  * Clicking on the Export iconwill open an options menu. Selecting “Export to PDF” or “Export to Image” will pop up a short-cut to the PDF/Image Export Options Boxes. Choose desired settings and click on the Export button to complete export.
* Print Preview
  * Selecting Print Preview from the Export menu will open a Print Preview window that contains more options for adjusting the layout and presentation of data.
* Export/E-Mail
  * In the Print Preview Window, export Items/DASHES solely or export and then send as attached files in an E-Mail. To Export alone, click on the upper File Types icon arrow to choose a file type and open the Export Options Box. To export and send in an E-Mail, click instead on the lower File Types icon and follow the same steps as in the export but with the added step that an E-Mail will be created with the file already attached.
* To Excel
  * To Export a data Item such as a Grid or Pivot to Excel, choose Print Preview from the Export icon menu in the Item’s Tools and Indicators section. In the Print Preview Window, click on the File Types icon arrow and choose XLS or XLSX as the file type from the Export To or E-Mail As options menus to open Excel Export Options Box

# CUBE Layout / Navigations

Cubes are specifically designed to link to various data sources and provide easy, fast analysis of data. Cubes provide a read-only lens over a data source whereby users can filter, sort, group and graph information.

* Cubes vs. Views
  * For each Cube, users can create, edit and save multiple Views. Each View is customized version of the same Cube data from a single record source.
* Master Views
  * Administrators can setup one or multiple <Master Views> for each cube and may edit these master views. In contrast, Users may view master views but man not modify / save any changes back to the system. Views created by users that are not master views may be edited by the user / creator.
* Cube Layout
  * The display of data is divided into two main sections: a) the designer area and b) the cube Area. The designer area is a holding area that shows which fields are used in the filter, row, column and data areas.

The cube area is detailed below.

## DATAQUEST Options

* Add fields
  * Add additional fields to selected Cube.
* Grid Options
  * Change general Cube properties (e.g., show or hide headers/totals).
* Field Properties
  * Change properties on a field by field basis (e.g., format, sort, etc.).
* Remove Filters
  * Enable users to review and remove existing filters.
* Pre-Filter
  * Filters data on expressions generated by users.
* Hide Collapsed Fields
  * Hides fields that have been collapsed for all records.
* Cell Format
  * Fields can be formatted to present data in a number of ways using <Format Type> and <Format String> in the Cell Format section of the Properties Tab
* Format Type
  * Filters data on expressions generated by users
    * For numeric data such as counts, dollar amounts, etc., set the [Format Type](http://documentation.devexpress.com/CoreLibraries/DevExpressUtilsFormatInfo_FormatTypetopic.aspx) property to [Numeric](http://documentation.devexpress.com/CoreLibraries/DevExpressUtilsFormatTypeEnumtopic.aspx).
    * For date/time values, set the Format Type to [DateTime](http://documentation.devexpress.com/CoreLibraries/DevExpressUtilsFormatTypeEnumtopic.aspx).
* **Format String**
  * To further specify the type/amount of information presented in a field, enter a Format String:
  * 

F) Group Intervals

Use the Group Intervals function to categorically limit the amount of information associated with a field so that it can filtered down. For example, to filter a date field by year, first Group Intervals by year (see Print Screen):

1) The <DueDate> field originally displays the Short Date Pattern, mm/dd/yyyy.

2) Select <DateYear> from the Group Interval dropdown.

3) Choose desired year or years on the Field Filter form (see Field Properties Chapter – Cell Format).