Instructions for Uploading to Application Builder
-------------------------------------------------

1.  Open Application Builder, and go to Settings-->Advanced Settings
2.  Go to Manage Custom Widgets, click Add
3.  Navigate to the PortalWidget_AppBuilder.zip file, and select the file.
4.  The Portal Widget should be added and available for use in the Application Builder.



Instructions to Upload to existing FlexViewer
---------------------------------------------
1.  Unzip the PortalWidget_AppBuilder.zip file, and copy the Portal folder under /src/widgets
2.  Copy the png files in /Portal/assets/images, into the /src/assets/images folder.
3.  Change the PortalWidget.xml configuration parameters (listed below)
4.  Add a widget reference to the application config.xml file



PortalWidget.xml configuration parameters
-----------------------------------------
 <arcgisonlineurl> -- can use either arcgis.com, or a Portal instance
 <tokenurl> -- the generateToken url, related to the <arcgisonlineurl> used
 <resultsperpage> -- how many results are returned per page search
 <defaultsearch> -- the initial search when the widget opens
 <defaultsortfield> -- the initial sort used, available options are ('','title','created','owner','avgRatings','numViews')
 <defaultsortorder> -- 'desc','asc'
 <columnsize> -- determines the size of the widget, 'full'=2 columns, otherwise 1 column