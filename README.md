# Trace
Flask + Jupter botebook+ selenuim + bokeh + pandas 集成的准指纹浏览器

下载地址：Trace-痕迹

**https://www.alipan.com/s/x6fqXe1jVg1**

# 使用说明

第1步：解压Trace1.0.8.exe，运行里面的Trace-痕迹.exe，B站，小红书的数据分析已经封装，直接使用即可。

第2步：如果Jupyter notebook打不开，说明本地虚拟环境存在问题:

(1)本机已有Python3.9环境，跳至第（4）步；

(2)本机没有Python3.9环境，下载python-3.9.9-amd64.exe，并安装。【推荐】

(3)本机没有Python3.9环境，下载Trace1.0.6版及requirements.txt,使用anaconda建立本地环境。

(4)用记事本打开Trace1.0.8/venv/pyvenv.cfg，将第1行中的home路径修改为本机的Python绝对路径，

注意，该路径下必须包含python.exe解释器！比如我的Python解释器绝对路径：F:\python3.9，如下：

home = F:\python3.9
include-system-site-packages = flase
version = 3.9.9
