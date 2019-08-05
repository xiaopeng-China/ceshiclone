# ceshiclone
ceshiclone
### git 和 git-hub
@(珠峰2019前端全栈VIP)
> git-hub：https://www.github.com
> 一个网站（一个开源的源代码管理平台），用户注册后，可以在自己账户下创建仓库，用来管理项目的源代码（源代码是基于git传到仓库中）
> 
> 我们所熟知的插件、类库、框架等都在这个平台上有托管，我们可以下载观看和研究源码等

#### Settings 用户设置
- Profile 修改自己的基本信息
- Account 可以修改用户名
- Security 可以修改自己的密码
- Emails 邮箱（必须进行邮箱校验）
- ......

#### 2.创建仓库
new repository -> 填写信息 -> Create repository
- public 公共仓库作为开源的项目
- private 私有仓库作为内部团队协作管理的项目

Settings ->
- 删除仓库 Delete this repository
- Collaborators 设置协作开发者
- Code 可以查看历史版本信息和分支信息

把本地仓库新新提到远程仓库
> 简历本地仓库和远程仓库的链接
> git remote -v    查看本地仓库和哪些远程仓库保持链接
> git remote add origin [git仓库地址]    让本地仓库和远程仓库新建一个链接 origin是随便起的一个链接名（可以改成自己想要的，只不过一般都用这个名字）
> git remote rm origin    删除关联信息
> 提交之前最好先拉取
> git pull origin master
> 把本地代码提交到远程仓库（需要输入github的用户名密码）
> git push origin master
> git clone [远程仓库git地址] [别名：可以不设置，默认是仓库名]
> 真是项目开发流程：
> 1. 组长或者负责人先创建中央仓库
> 
