#效果图先行#

 
 


![58同城效果](http://upload-images.jianshu.io/upload_images/166866-7d4158de2ce40a9a.gif)

![实现的效果](http://upload-images.jianshu.io/upload_images/166866-6e4012c1949aaa7a.gif)

#地址:#
[github 直达](https://github.com/zzz40500/android-shapeLoadingView)
#usage#

布局上
~~~

<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools" android:layout_width="match_parent"
    android:layout_height="match_parent"         android:paddingLeft="@dimen/activity_horizontal_margin"
  android:paddingRight="@dimen/activity_horizontal_margin"
    android:paddingTop="@dimen/activity_vertical_margin"
   android:paddingBottom="@dimen/activity_vertical_margin" tools:context=".MainActivity">

    <com.mingle.widget.LoadingView
        android:id="@+id/loadView"
        android:layout_width="fill_parent"
        android:layout_height="fill_parent"/>
</RelativeLayout>

~~~

动画自动加载
