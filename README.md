# XRefreshView

支持 Androidx 版本， 
原作者github： https://github.com/huxq17/XRefreshView

### Usage
----

#### Gradle

懒得上传到 jcenter，有需要的自己编译吧哈

```groovy
dependencies {
    implementation(name:"XRefreshView", ext: "aar")
    //依赖下面的库
    implementation 'androidx.recyclerview:recyclerview:1.1.0'
    implementation 'androidx.legacy:legacy-support-v4:1.0.0'
    implementation 'androidx.cardview:cardview:1.0.0'
}
```

## 最新的使用说明请移步[原作者的博客](http://blog.csdn.net/footballclub/article/details/46982115 "description")

## 效果图

|松开加载更多的Recyclerview|带Banner的Recyclerview| LinearLayout样式的Recyclerview|
|:-----|:-----|:-----|
| <img src="gif/xrefresh_releasetoloadmore.gif" width="280" height="475" /> | <img src="gif/xrefresh_banner.gif" width="280" height="475" /> | <img src="gif/xrefresh_linearlayout.gif" width="280" height="475" /> |

|GridLayout样式的Recyclerview|Staggered样式的Recyclerview|
|:-----|:-----|
| <img src="gif/xrefresh_gridlayout.gif" width="280" height="475" />| <img src="gif/xrefresh_staggeredlayout.gif" width="280" height="475" />|

|GridView|自定义View|笑脸刷新|
|:-----|:-----|:-----|
| <img src="gif/xrefresh_gridview.gif" width="280" height="475" />| <img src="gif/xrefresh_customview.gif" width="280" height="475" />|<img src="gif/xrefresh_smile.gif" width="280" height="475" />|

还有listview,scrollview，webview等其他的view就不一一截图了。**建议把此项目下载下来，然后跑到手机上看效果，例子都在app module里。**

### 更新日志：<br/>
    
    2020-4-4
    原半不支持androidx，本版本只将库切换到 androidx，没有经过大量测试
    
 
    
