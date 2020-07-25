# HellohaoWallpaper
基于SpringBoot搭建的的高清壁纸图片站，对接的360壁纸api。


（如果不会可以用我打包好的jar包直接部署就可以。在`/成品jar包下`）
![t1_副本.jpg](https://f000.backblazeb2.com/file/hellohaoimg/github/wallpaper03.png)

![t2_副本.jpg](https://f000.backblazeb2.com/file/hellohaoimg/github/wallpaper02.png)

![t2_副本.jpg](https://f000.backblazeb2.com/file/hellohaoimg/github/wallpaper01.png)

**打包：**

用maven命令打成jar包就可以。
```shell
mvn clean
mvn package
```

**部署：**
然后把jar包放到你服务器的某个目录下，进入此目录然后执行即可部署完成
```shell
java -jar hellowallpaper.jar
```

然后访问：你的域名:8089即可访问,这样，你的网站就部署成功了。
**如果你想修改端口进入项目目录/src/main/resources在application.properties修改即可**

