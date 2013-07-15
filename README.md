# Android Latitude and Longitude Picker

Android code to display a location picker. The user can select a point on the map, and the code returns the latitude and longitude value, and the name of the place according to Google.

(For the time being this project works as a wrapper for the jQuery latitude and longitude picker project. Read about it more: [github.com/wimagguc/jquery-latitude-longitude-picker-gmaps](https://github.com/wimagguc/jquery-latitude-longitude-picker-gmaps))

## Future plans

This is a simple wrapper project just yet. It's fully usable (as seen in the Divespy Android app), but the plan is to add these modifications as soon as possible:

* a standalone Activity which you can call with startActivityForResult on Android
* use a native Google Maps object instead of the jQuery one

## Install

Simply create and Android project and add the following files:

* com/wimagguc/locationpicker/LocationPickerActivity.java
* assets/locationPicker/*
* res/layout/activity_location_picker.xml
* res/values/strings.xml

Then modify the AndroidManifest.xml to include this activity:

```
<application …>
  <activity android:name=".LocationPickerActivity"/>
</application>
```

The app is should work on every API v8 and API v17 device.

## License

Do with the code whatever you please.

This code uses the jQuery Javascript library and the Google Maps API. To read more about these, go to: [jquery.com/](http://jquery.com/) and [developers.google.com/maps/](https://developers.google.com/maps/)

## Used at

* [Dive Log](https://play.google.com/store/apps/details?id=com.divespy.android&hl=en) Android app

(If you are using this code for another project, please add it here - or just let me know and it will be featured here.)

## About

Richard Dancsi  
[www.wimagguc.com](http://www.wimagguc.com/)  

twitter: [@wimagguc](http://twitter.com/wimagguc)  
linkedin: [linkedin.com/in/richarddancsi](http://linkedin.com/in/richarddancsi)  
gplus: [plus.google.com/u/0/115939246085616544919](https://plus.google.com/u/0/115939246085616544919)  
