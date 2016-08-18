# jsp.study
# JDK的安装
- 安装包下载好之后，双击安装包进行安装，会让你两次选择安装路径，第一次是JDK的路径，第二次是jre的路径；记住JDK的安装路径
- 配置环境变量；分别为JAVA_HOME值为jdk安装路径，如：D:\Java\jdk1.8.0_25（无此选项则自己创建）。Path ：将;%JAVA_HOME%\bin;添加至末尾 
- 测试JDK是否安装成功。在dos窗口中输入java -version，java，javac

# 安装tomcat
- 下载地址：http://mirror.bit.edu.cn/apache/tomcat/tomcat-8/v8.5.4/bin/apache-tomcat-8.5.4-windows-x64.zip
- 解压安装包
- 打开bin文件夹---双击startup.bat;系统会打开一个dos窗口，即启动成功
- 打开bin文件夹---双击startup.bat;系统会打开一个dos窗口，即启动成功；如果未打开dos窗口或者dos窗口一闪而过，可能是jdk的配置出错，请注意检查
- 最后在浏览器中输入http://localhost:8080,出现如图所示情况则tomcat安装成功；