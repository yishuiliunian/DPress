# DPress

DPress is a simple blog powered by Django.

## demo site:

+ site url: [http://dpress.sinaapp.com/](http://dpress.sinaapp.com/)
+ admin url: [http://dpress.sinaapp.com/admin/](http://dpress.sinaapp.com/admin/)
+ username: guest
+ password: guest

## Features

+ [Markdown](http://daringfireball.net/projects/markdown/)
+ use [EpicEditor](http://epiceditor.com/) as Markdown Editor.
+ [DISQUS](http://disqus.com/)
+ Code Highlight. Syntax: [Fenced Code Blocks](http://packages.python.org/Markdown/extensions/fenced_code_blocks.html)
+ use [Django FileBrowser](https://github.com/sehmaschine/django-filebrowser) to upload files.
+ use [flatpages](https://docs.djangoproject.com/en/dev/ref/contrib/flatpages/) to manage custom page.
+ GOOGLE ANALYTICS
+ RSS
+ Tags

## run on Django dev server

+ Clone DPress repository from git://github.com/vicalloy/DPress.git
+ install virtualenv: pip install virtualenv 
+ use scripts env.rc(source env.rc) to create and start DPress environment.
+ $mg is a shortcut for "python manage.py "
+ $mg syncdb
+ $mg migrate
+ $mg runserver
+ DPress Admin http://127.0.0.1:8000/admin/
+ DPress http://127.0.0.1:8000/

## config

+ copy sites/settings/pre.sample to sites/settings/pre.py and config it.
+ copy sites/settings/local.sample to sites/settings/local.py and config it.

## use theme moment

+ moment is a theme designed by [Hsiaoming Yang](http://lepture.com)
+ copy sites/settings/pre.sample to sites/settings/pre.py
+ modify pre.py and set "SETTINGS = 'theme_moment'"
