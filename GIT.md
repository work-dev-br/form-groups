

git add .
git commit -m "Commit ?"
git push --set-upstream origin desenv




…or create a new repository on the command line

echo "# form-groups" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/work-dev-br/form-groups.git
git push -u origin main
                

…or push an existing repository from the command line

git remote add origin https://github.com/work-dev-br/form-groups.git
git branch -M main
git push -u origin main