


# 拉取代码到本地
git clone git@github.com:xuming1986/XXDScorecard.git
cd D:/home/ming.xu/git/gitest1/XXDScorecard


# 修改代码并上传到远程仓库
vim test1.py
git add test1.py
git commit -m '添加test1.py'
git push -u origin master 

# 创建分支
## 切换到基础分支，如主干
git checkout master

## 创建并切换到新分支

git checkout -b panda

git branch可以看到已经在panda分支上

## 更新分支代码并提交

git add *

git commit -m "init panda"

git push origin xm

## 在git代码管理界面经可以看到panda分支了，成功~~


