-(paso 11) utilice el comando git reset --hard HEAD~1 para volver un paso atras y
utilizando el --hard para eliminar el working directory

-(paso 12) utilice el comando git reflog para buscar el ultimo commit y git
reset --hard (id encontrado en reflog) para volver a rehacer el commit

-(paso 13) No causo conflictos al ser un fast foward y ser hijo del padre

-(paso 19) Si causo conflictos debido a tener las mismas lineas alteradas
tanto en styled como htmlify

-(paso 21) No causo conflicto al ser un fast foward

-(paso 25) Utilizamos git log --graph

-(paso 26) No si queremos que siga apuntando al commit en el que estaba master

-(paso 27) Utilizamos git log --graph para ver el id y git reset (id) para
deshacer el merge sin afectar al working copy

-(paso 28) Utilizamos git reflog para volver con un git reset (id) a antes
para deshacer el merge

-(paso 29) git branch -D title

-(paso 30) Al eliminar la rama title nos informa que se ha borrado el tag
de la rama que estaba en id tal y realizar un git merge id desde master, a
su vez podriamos utilizar git reflog para buscar el id

-(paso 32) Con git log o git log --graph podemos buscar el commit inicial y
utilizar git checkout (id) para llegar a el

-(paso 33) Deberiamos utilizar git reflog para ver las interacciones
realizadas y asi ver cual es el commit de cuando le pusimos titulo al programa
