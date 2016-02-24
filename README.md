###Starting a new project

1) Clone a copy of the News Apps Template from Chris' Git page.
2) Rename the repository locally. Already in a single git comand.

Git command to clone and rename a repository locally:
$ git clone [repository address here] file-name-here 



###Save to YOUR repository:

1) Add all untracked files to the repository.
```
$ git add .
```
OR 
```
$git add -A
```

2) Create a new repo on YOUR Git page
Open your Git page, create and name a new repository.

3) Remove the original ORIGIN (which links to Chris' Git page)
```
$ git remote rm origin
```

4) Add YOUR origin to the repository
```
$ git remote add origin [address copied from your newly-created repo]
```

5) Commit your changes.
```
$ git commit -am "Describe your changes here"
```

6) Push to your new repository.
```
$ git push origin master
```

###Git Markdown Cheatsheet:
https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet