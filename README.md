# Git Orders

## 本地git

### 初始化
git init

### 设置用户名
git config --global user.name 'Xueshi Lu'

### 设置邮箱
git config --global user.email '...@gmail.com'

### 查看git的config
git config -l

### 状态
git status

### 添加add
git add .
git add sample.txt
git add *.txt

### 删除add
git rm --cached sample.txt

### 添加commit
git commit
git commit -m 'changed sample.txt'

### 添加分支
git branch sample

### 切换分支
git checkout sample

*分支内commit的内容，不会在另一个分支里出现

### 合并分支
git merge sample

### 忽视文件
创建 .gitignore

## git - github
列出已经存在的远程分支
git remote

### 添加远程仓库
git remote add origin git@github.com:xueshilu/myapps.git

### push到远程仓库
git push -u origin master

### clone到本地
git clone address

### 拉取到本地 (将远程主机origin的master分支拉取过来，与本地的brantest分支合并)
git pull origin master:brantest
git pull origin master
