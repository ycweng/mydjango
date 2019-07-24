# errors
## In python 3.7, django 1.11.9
-   File "C:\Users\weng1\Documents\python_workshop\mydjango\lib\site-packages\django\contrib\admin\widgets.py", line 151
    '%s=%s' % (k, v) for k, v in params.items(),
- SyntaxError: Generator expression must be parenthesized
- 刪掉最後的逗號

## Django commands
- django-admin.py startproject <project_name>	建立 Django 專案
- python manage.py -h <command_name>	查看 Django commands 的使用方法
- python manage.py runserver	啟動開發伺服器
- python manage.py startapp <app_name>	新增 Django app
