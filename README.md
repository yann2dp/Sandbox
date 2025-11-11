# initiation a git

## download le projet pour y travailler:

git clone https://github.com/yann2dp/Sandbox

## état de l'espace de travail:

git status

## Ajout d'un fichier dans l'espace pret a commiter

git add <fichier>

## interaction avec le server distant

Télécharger la base de donnée distante:
$ git fetch origin

Upload local branch to remote server:
$ git push origin <local_branch>:<new_branch_on_server>

Example:
$ git push origin dev/smi:dev/smi

## Commiter les changements:

git commit -sm "<Message>" <fichier>

ou

git add <fichier>

git commit -sm "<Message>"

## voir la difference entre l'espace de travail et le dernier commit:

git diff


