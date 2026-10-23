# Variables y Tipos de Datos en Python
1. ¿Qué son los Datos en Informática?
Los datos son representaciones simbólicas (información o valores) que recibe el computador a través de distintos medios para ser manipulados y procesados mediante algoritmos.
- Tipos de datos
- Numericos
- logicos
- Cadena de caracteres

2. Tipos de Datos Básicos en Python
Enteros (int): Números positivos o negativos sin decimales.

* Ejemplos: 12, 0, -2.

* Flotantes o Decimales (float): Números que contienen dígitos después de un punto decimal.

* Ejemplos: 1.9, 0.2, -3.0.

* Nota: En Python se usa punto (.), no coma (,).

* Lógicos o Booleanos (bool): Representan valores de verdad.

* Valores: True (Verdadero) y False (Falso).

* Nota: Deben escribirse siempre con la primera letra en mayúscula (True, False).

* Cadena de Caracteres (string / str): Texto o expresiones formadas por caracteres delimitados por comillas simples (' ') o dobles (" ").

* Ejemplos: 'Hola mundo', "A quien madruga un buen café le ayuda", 'A'.

* Diferencia clave: "22" (string) no es igual a 22 (int). El primero es un texto y el segundo es un número entero con el que se pueden hacer operaciones matemáticas.
3. Comentarios en Python
Se inician con el símbolo de numeral o hashtag (#).

El intérprete de Python ignora estas líneas, por lo que no afectan la ejecución del código.

4. Variables
Definición: Es un espacio reservado en la memoria que almacena un dato. Puede imaginarse como una caja etiquetada donde guardas un valor.

Variabilidad: Su contenido puede cambiar durante la ejecución del programa.

Reglas obligatorias para nombrar variables:
Pueden contener letras, números y guiones bajos (_).

No deben iniciar con un número (ej. 1tarea es incorrecto; tarea1 es correcto).

No deben usar guion medio (-) (ej. fecha-1 es incorrecto; fecha_1 es correcto).

No pueden ser palabras reservadas del lenguaje.

Buenas prácticas:
Elegir nombres descriptivos que representen el dato almacenado (ej. nombre, edad, precio_venta). Evitar nombres genéricos como x o y.

Para nombres con múltiples palabras, usar estilo camelCase (precioVenta) o snake_case (precio_venta).

Se recomienda que no excedan los 15 caracteres y no comiencen con mayúscula.

5. Palabras Reservadas
Son términos que tienen un significado gramatical o funcional especial en Python y no se pueden utilizar como nombres de variables (por ejemplo, print).

6. Operador de Asignación y Formas de Asignar
El símbolo igual (=) es el operador de asignación. Sirve para crear una variable o modificar su valor si ya existía.
* Asignación simple:
```Python
nombre = "Alejo"
edad = 24
```
* Reasignación:
```Python
edad = 24
edad = 18  # Reemplaza el valor anterior
```
* Asignación en la misma línea (separada por ;):
```Python
base = 5; altura = 2; area = base * altura
```
* Asignación múltiple:
```Python
base, altura, color = 5, 7, "rojo"
```
* Asignación del mismo valor:
```Python
base = altura = 2.5
```
* Asignación por intercambio de valores:
```Python
base, altura = altura, base
```
Video del dia: https://www.youtube.com/watch?v=dbICRLZ46Qw
