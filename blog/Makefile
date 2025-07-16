install:
	sudo apt install jekyll
	jekyll build

publish:
	jekyll build
	rsync -avz --delete -e ssh _site/ xudifsd@xudifsd.org:/var/www/blog
