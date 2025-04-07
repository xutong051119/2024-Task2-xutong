# 总结与反思

## 所使用的Git命令

- git clone 仓库地址 -- 克隆仓库

- git add -- 添加文件到Git暂存区

- git commit -m "更改说明" -- 提交更改到本地仓库

- git push origin 分支名 -- 将更改推送到远程仓库

- git branch --查看本地分支

- git branch --查看远程分支

- git branch 新分支名称 --创建新分支

- git checkout 分支名称 --切换分支

- git merge 分支名称 -- 将该分支的代码合并到当前分支

## 所使用的Conda命令

- conda create --name <ENV_NAME> <PACKAGE>=<VERSION> --创建一个新的环境并下载指定的包及其依赖项

- conda activate <ENV_NAME> --激活环境

- conda info --envs --查看环境列表

- conda install conda-project -- 安装软件包conda-project

- conda-project init --创建文件

- conda-project lock --锁定项目环境

- conda env export > environment.yml --导出环境

## Anaconda 环境配置的优点与难点

- 优点：提供独立的工作空间，可以在里面安装特定版本的软件包、依赖项等；不同的环境间可以快速切换，可以同时管理多个不同项目；环境适合测试新的软件包，并不影响稳定的开发设置

- 难点：环境管理较为复杂

## Git分支管理中的经验

- 通过创建分支对项目的版本进行更加方便的管理，但是需要规范使用git命令以及markdown语法，在分支管理中可以进行分支的创建、切换与合并操作，便于开发和测试

## 部署过程中遇到的问题及解决方案

- 在本次学习任务中并未遇到问题
