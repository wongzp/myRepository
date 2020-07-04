
# 实验目的

 内容包括 Git 软件的安装和简单使用，比如 增加文件，提交，创建分支，增加远程，下拉、上推，合并等内容。

# 实验平台
windows 10 64位

# 实验前准备
新建一个文件夹，当做一个项目文件

# 实验内容

##下载Git
第一步：到Git官网https://git-scm.com/download/win直接下载对应的版本。安装过程一直选择默认配置即可

同时也可以下载一个GUI，我们这里使用内置的GUI
![](./git-img/download-git-1.png)

第二步：安装完成后，回到桌面或者某个文件，点击右键，如果有出现Git GUI Here和Git Bash Here就表明安装成功了
![](./git-img/download-git-2.png)

##开始使用Git
先在目录下右键，点击Git Bash Here，在Git命令窗口输入git init初始化本地仓库。
![](./git-img/gitGui-2.png)

回到目录，右键点击Git Gui Here打开GUI面板。图片中已经介绍到部分常用功能（创建分支、合并分支、查看历史、提交）的按钮的位置
![](./git-img/gitGui-1.png)

点击Edit----options，在里面输入UserName和Email Address
![](./git-img/gitGui-3.png)

##增加文件
在上面的Git GUI面板上已经标注了各部分区域的主要作用。

第一步：在打开Git GUI的目录下创建一个test.txt，内容是：测试文本

第二步：打开Git GUI或者在里面刷新一下，就可以看到如下图:左上方显示test.txt，右边可以看到test.txt的内容
![](./git-img/commitFile-1.png)

第三步：将test.txt拉到左下方Staged Changes区域里，或者点击test.txt前面的标签，就可以将test.txt放到staged changes里。

注意：只有在Stagde Changes里的文件才会被提交

第四步：在右下方的文本框输入本次提交的附加内容（通常为描述提交内容）

第五步：点击旁边的commit
![](./git-img/commitFile-2.png)

可以在Repositiry----Visualize master History中看到相关提交内容
![](./git-img/commitFile-3.png)

##提交文件到仓库

##创建一个分支

##增加远程

##下拉

##上推

##合并文件


# 实验总结