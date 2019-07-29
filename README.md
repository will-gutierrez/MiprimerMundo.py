# MiprimerMundo.py
'''
Reeborg recorre el mundo hasta llegar a la manzana, 
posteriormente coge la manzana, deja una banana y 
regresa a su posición  inicial (home).
'''
print("Hola soy Reeborg")
print("Hoy haré mi primera misión")
repeat 3:
  move()
move()  
#pause()
take("apple")
#pause()
put("banana")
turn_left()
turn_left()
#pause()
repeat 3:
    move()
move() 
turn_left() 
turn_left()
# Autor: William Gutierrez 
# Fecha: 29 de julio de 2019
