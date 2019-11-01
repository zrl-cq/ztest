git is a version contorl system.
git is free software.
git config --gloabal user.name 
git config --gloabal user.email

git add xuexi2.txt 
#添加文件
git commit -m "tijaiobeizhu1"
#提交到本地库
git status
#上次add或commit前文件变动
git checkout --  filename
#撤销改变
git config --glabal credential.helper store
#输入密码保存
git log
#察看库版本
git reset -hard  版本id
#版本退回
git reset -HEAD
#退回到上个版本
git clone https://github.com/zrlrunlin20180821/gittest.git
#克隆远程库到本地
git checkout -b dev
#创建dev分支，然后切换到dev分支：
git branch dev
创建dev分支
git checkout dev
切换到dev分支
git branch
察看当前分支
