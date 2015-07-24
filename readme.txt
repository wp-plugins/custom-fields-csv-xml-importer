=== CIO Bulk Importer ===
Contributors: VisualData
Donate link: http://vipp.com.au/
Tags: custom fields, custom fields import, wp all import, csv import, pods csv import, xml import, pods xml import, pods custom content types and fields, pods, relationship fields, bi-directional relationship fields, multiple select relationship fields, multiple select bi-directional relationship fields, custom post types, CMS migration, website migration, website update, data feed, data import, data update, automatic update, cron import, automatic import,bulk import, bulk edit, fast import, quick import
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html
Requires at least: 4.1.0
Tested up to: 4.2.2
Stable tag: 1.0.0

Simple, easy, fast and flexible, CIO Bulk Importer processes large data sets from any XML or CSV files to enable efficient update of websites and databases.

== Description ==

Are you planning a new website with many records to update, or have you got a good looking website but spent too much time keeping the content accurate and updated? CIO Bulk Importer is part of the efficient solution to improve work flow and make website updating simple and easy.

CIO Bulk Importer is an add-on linking the following two powerful tools together in delivering an efficient and affordable solution for small and medium businesses.

1. [PODS](https://wordpress.org/plugins/pods/). PODS is a free, simple, flexible and powerful CMS framework designed for high performance with large data sets. You can use PODS to extend content types with custom fields, or create custom content types of your own. PODS unleashes the power of Wordpress in creating highly customised CMS. 

2. [WP All Import](http://wordpress.org/plugins/wp-all-import/). WP All Import is a well developed tool to handle imports from larger XML and CSV files. The free version comes with logging, detection of duplicate records, and templates for future imports and updates.  

Together with Pods and WP All Import, CIO Bulk Importer provides a simple and easy way to build a high performance website, import large data sets and manage ongoing updates from external data sources.  

Accurate and timely website information is crucial to some professions, such as property developers and real estate agents. Mistakes are costly. With CIO Bulk Importer, the principal or person in charge can review information before uploading to the website reducing chances of errors. 


How Does It Work


CIO Bulk Importer automatically detects all your custom fields created with PODS and display them in step 3 of WP All Import. 

The left side shows all of the custom fields that you can import to and the right side displays the data from your XML/CSV file. Then you can simply drag & drop the data from your XML or CSV into the PODS custom fields to import them. 

The CSV or XML can be in any order under any column header, and big files are broken into small chunks to allow importing to shared hosting sites, thanks to the great work by the WP ALL Import team. 

CIO Bulk Importer is a handy tool for people migrating big volume of data from other sources to PODS websites, or regularly importing and updating data on PODS websites, such as real estate property listing websites, or book keeping websites. Simply create custom content types and fields using PODS for fast development and performance, export data to CSV or XML from your data sources or receive from suppliers/clients/partners, and import into PODS custom fields with ease. 


CIO Bulk Importer was used on a shared hosting website created with PODS to import 25,000 records in one go successfully.  

CIO Bulk Importer needs both WP All Import and PODS plugins installed and activated in order to work. Both WP All Import and PODS are freely available in the plugin repository.


= Why you should use the CIO Bulk Importer =


* Simple, easy and fast tool to migrate data or regularly import/update data to PODS websites. 

* Create or update relationship fields with known ID.

* Create or update image fields with known ID.

* Import new posts, pages, or custom post types with pods custom fields.

* Support pods custom fields stored in separate tables and meta fields.

* Update pods custom fields for existing posts, pages, or custom post types already published on your site.

* Track imported records to avoid duplicates (feature of WP All Import).

* Import template for future use (feature of WP All Import).

* Compatible with other WP All Import add-ons.

The CIO Bulk Importer is compatible with PODS (free) and [the free version of WP All Import](http://wordpress.org/plugins/wp-all-import "WordPress XML & CSV Import"). It can be used along other add-ons for WP All Import.


= CIO Bulk Importer Professional Edition =


The CIO Bulk Importer free edition detects and handles importing to pages, posts extended by pods and new custom post types created with pods. It doesn't handle other content types, such as Advanced Content Types, users or comments extended by PODS.

[The CIO Bulk Importer Professional Edition ](https://vipp.com.au/) adds the following features:

* Handle importing of other pods content types including Advanced Custom Types, Comments and Users extended with PODS, in addition to pages, posts and custom post types.

* Automatically search and assign relationship field ids during import to a live website.

* Support bi-directional relationship import and update on live sites.

* Support multisites

* Priority support.

* Customisation of the add-on to suit your unique data importing and updating needs.

[Upgrade to Professional Edition](https://vipp.com.au/) to access these premium features.


You may also consider upgrading to [the professional edition of WP All Import](http://www.wpallimport.com/order-now/) for premium support and the following extra features:

* Import files from a URL: Download and import files from external websites, even if they are password protected with HTTP authentication. 

* Cron Job/Recurring Imports: WP All Import Pro can check periodically check a file for updates, and add, edit, delete, and update the your custom fields.

* Custom PHP Functions: Pass your data through custom functions by using [my_function({data[1]})] in your import template. WP All Import will pass the value of {data[1]} through my_function and use whatever it returns.

* Access to premium technical support.


Special thanks to soflyy, wpallimport who have developed WP All Import and made the add-on API available.



== Installation ==

First, install and activate [WP All Import](http://wordpress.org/plugins/wp-all-import "WordPress XML & CSV Import") and [Pods - Custom Content Types and Fields ](https://wordpress.org/plugins/pods/).
If there are issues installing these two plugins, please look for solutions in the support forum or contact the plugin authors.

Then install the CIO Bulk Importer. This add-on needs both PODS and WP All Import installed and activated.

To install the CIO Bulk Importer, either:

* Upload the plugin from the Plugins page in WordPress

* Unzip custom-fields-csv-xml-importer.zip and upload the contents to /wp-content/plugins/, and then activate the plugin from the Plugins page in WordPress.

The PODS Add-On will appear in Step 3 of WP All Import. See screenshots for details.

[Upgrade to Professional Edition](https://vipp.com.au/) to access premium features, and priority support.



== Frequently Asked Questions ==

= I installed and activated this plugin, but can’t find out any menu =

The add-on needs WP All Import and Pods to work. First verify these two plugins are installed and activated. Create a new import under the menu of All Import, upload a test cvs or xml file, then in step 3, you will see custom fields created with Pods. 

= I can import some pods, but have issues importing others. the process is killed by the server =

Possible causes - please check pods fields settings. Mandatory pods fields must be assigned a value for the import to succeed.

= I can't import into some custom fields created with pods =

Possible causes 1 - custom field names shared among pods.

The CIO Bulk Importer detects and lists ALL your custom fields created with PODS in one form in step 3 of the import process, even though you are importing ONE pods content type at a time. The custom fields are grouped by pods labels.

If a field name is used in multiple pods, multiple input cells will be generated in the form with the same field name, and only the value of the last input cells (possibly blank by default) will be saved. 

To avoid this problem, please try to use unique field name when creating your pods. If you have to use the same field name in multiple pods, then you can drag and drop the value to the last input cell.

Possible causes 2 - custom defined list in relationship field

Please check the custom defined list in your relationship field. The value supplied in the csv or xml file has to be in the custom defined list to be imported.

= I can see a pods content type but can't import data to the pod =

CIO Bulk Importer free edition detects and lists all your pods content types however it supports importing and updating of post types only, including new custom post types created with pods, and posts/pages extended with pods. 

Please consider upgrading to [CIO Bulk Importer Pro](http://www.vipp.com.au) to import other content types (including Advanced Custom Types and extended Users). 

= My csv file has many rows, but only the header row is detected  =

This is probably caused by improperly formatted csv files, such as the CSV files saved by Microsoft Excel. You may try to open the csv files using another spreadsheet program such as the free OpenOffice or LibreOffice, save as a new CSV file and see whether the problem is resolved.


== Changelog ==

= 1.0.0 =
* Initial release on WP.org.


== Upgrade Notice == 

This add-on has been developed and tested on wordpress 4.2.2 with pods 2.5.3 and WP All Import 3.3.0 installed and activated. It may also work on old versions.


== Screenshots == 

1. In step 3 of WP All Import importing process, PODS custom content types are detected and listed. 

2. Choose your content types to import

3. Drag and Drop your data fields from the xml or cvs file. A few clicks, have a cuppa. Done!



== Support ==


We do try to handle support for our free version users at the following e-mail address:

E-mail: support@vipp.com.au

Support for free version customers is not guaranteed and based on availability. For premium support, please purchase [CIO Bulk Importer Pro](http://www.vipp.com.au).
