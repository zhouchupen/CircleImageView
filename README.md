# CircleImageView

Android自定义圆形ImageView

![](http://upload-images.jianshu.io/upload_images/2746415-8106d51f3d3d784c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## Installing

Users of your library will need add the jitpack.io repository:

```gradle
allprojects {
 repositories {
    jcenter()
    maven { url "https://jitpack.io" }
 }
}
```

and:

```gradle
dependencies {
    compile 'com.github.zhouchupen:CircleImageView:v1.0'
}
```

Note: do not add the jitpack.io repository under `buildscript` 

## Adding a sample app 

If you add a sample app to the same repo then your app needs to depend on the library. To do this in your app/build.gradle add a dependency in the form:

```gradle
dependencies {
    compile project(':library')
}
```

where 'library' is the name of your library module.

## Using

You may need this to use the linegraph.  Put this into your xml file:
```xml
<com.scnu.zhou.widget.CircleImageView
     android:id="@+id/civ_userheader"
     android:layout_width="64dp"
     android:layout_height="64dp"
     android:src="@drawable/picture"
     app:border_color="#ffffff"
     app:border_width="2dp"/>
```
