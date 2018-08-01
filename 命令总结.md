# Window命令总结：
## 1.基本操作
- cd 文件名 --进入某个文件夹
- cd .. --返回上一层
- dir --查看当前的具体路径(window)
## 2.简单操作本地仓库：
- git init --- 导入为可执行git文件
- git status --- 查看本地修改内容
- git diff 路径 --- 查看具体不通点
- git rm --- 移除文件
- git branch --- 查看所有分支
- git branch -a --- 查看当前所在分支
- git branch- d 分支名 --- 删除此分支，此分支合并的情况下
- git branch -D 分支名 --- 强制删除此分支，不论此分支什么状态
- git checkout 分支名 --- 切换到此分支名
- git checkout -b 分支名 --- 新建分支并且切换到此分支
- git checkout 路径 --- 忽略提交时产生的不同点
- git add -A --- 添加所有文件到本地缓存区
- git add -u -- 添加被修改和被删除的文件到本地缓存区，不包括新文件
- git add . -- 添加新文件和被修改的文件奥本地缓存区，不包括被删除的文件
- git commit -m "" --- 暂存区文件添加为工作区
- git log --- 查看log日志
- git reset --hard logID --- 回退到此log版本
## 3.操作远程仓库：
- git remote add origin 地址 --- 关联远程仓库
- git remote -v --- 查看关联的远程仓库
- git remote rm 仓库名 --- 删除关联的远程仓库
- git clone 地址 --- 克隆远程仓库
- git remote add upstream origin 地址 --- 关联上游仓库
- git push origin master --- 推送代码到远程仓库master分支
- git push -u origin master -f 强制推送本地代码到远程仓库(覆盖远程仓库)
- git pull origin master --- 从远程仓库master分支拉取代码到本地
- git fetch upstream 从远程上游仓库获取最新代码到本地
- git rebase upstream/master 从远程上游仓库的master分支拉取代码到本地
- git rebase --skip 跳过本次rebase
- git rebase --continue 解决冲突继续下一步的操作
- gir rebase --about 终止此次rebase
- git merge 分支名 --- 远程上游仓库与本地仓库合并

# linux命令总结：
## 1.基本操作：
- cd 文件名 -- 进入某个文件夹
- cd .. -- 返回上一层
- pwd --查看当前的具体路径(linux)
- ls -- 显示目标内容列表
- cp -- 将源文件者目录复制到目标文件或目录中
- mv -- 对文件或者目录重命名
- rm -- 删除给定的文件或目录
- rmdir -- 删除空目录
## 2.对文件的操作
- unzip -- 用来解压shell中的压缩文件
- gzip -- 用来压缩文件
- diff -- 比较给定的俩个文件的不同
- cmp -- 比较俩个文件的差异
- find -- 在指定目录下查找文件
	
	
	
	