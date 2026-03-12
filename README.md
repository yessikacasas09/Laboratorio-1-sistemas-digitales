# Laboratorio 1 - Sistemas Digitales
 
## Integrantes
- Yessika Vannesa Casas Casas
- Sergio Esteban Alarcon Valbuena
- Angel Gabriel Brito Barrero

 
# Punto 1: Oscilador Multivibrador Astable (Timer 555)
 
## Objetivo
Desarrollar un montaje de un oscilador astable con un periodo aproximado de 2 segundos utilizando un temporizador 555.
 
## Componentes
- Protoboard
- Timer 555 (NE555 o TL555)
- Regulador LM7805
- Resistencias
- Capacitor electrolítico
- LED
- Batería de 9V
- Cables
 
## Funcionamiento
 
El temporizador 555 funciona como un multivibrador astable, generando una señal cuadrada continua.
 
El capacitor se carga y descarga a través de las resistencias, lo que genera el cambio entre estado alto y bajo en la salida.
 
Cuando la salida está en alto el LED se enciende y cuando está en bajo el LED se apaga.
 
## Fórmula del periodo
 
T = 0.693 (R1 + 2R2) C
 
Donde:
 
T = periodo total  
R1 = resistencia 1  
R2 = resistencia 2  
C = capacitor

<img src="https://github.com/user-attachments/assets/da14cc16-7bed-4ab9-adeb-8a8abc78c49c" alt="Descripción" width="700">



https://youtube.com/shorts/wdKRmZBDoWY?si=31rv3fe2yFyQoYHq

 
Para este laboratorio se calculó un periodo cercano a **2 segundos**.
 
# Punto 2: Compuertas Lógicas
 
## Objetivo
Reconocer el funcionamiento de diferentes compuertas lógicas utilizadas en sistemas digitales.
 
## Compuertas utilizadas
 
- AND
- OR
- NOT
- NAND
- NOR
- XOR
 
## Circuitos Integrados utilizados
 
- 74LS08 → AND
- 74LS32 → OR
- 74LS04 → NOT
- 74LS00 → NAND
- 74LS02 → NOR
- 74LS86 → XOR
 
## Funcionamiento
 
Las compuertas lógicas realizan operaciones booleanas con señales binarias.
 
Las entradas se generan mediante un **DIP Switch**, que permite representar valores lógicos 0 y 1.
 
El LED se conecta a la salida para visualizar el resultado de la operación lógica.
 
## Tabla de verdad ejemplo (AND)
 
| A | B | Salida |
|---|---|---|
|0|0|0|
|0|1|0|
|1|0|0|
|1|1|1|
 



 
# Punto 3: Conversor Binario a Hexadecimal
 
## Objetivo
 
Diseñar un circuito capaz de convertir un número binario de 4 bits en su representación en un display de 7 segmentos.
 
## Funcionamiento
 
Las entradas A, B, C y D son generadas mediante un **DIP switch**.
 
Estas entradas representan un número binario entre:
 
0000 y 1111
 
Esto corresponde a los números decimales de **0 a 15**.
 
Las compuertas lógicas procesan las señales y activan los segmentos correspondientes del display.
 
 
# Conclusión
 
Este laboratorio permitió comprender el funcionamiento de los circuitos digitales básicos, incluyendo el uso del temporizador 555, compuertas lógicas y la conversión de números binarios a su representación en un display de 7 segmentos.

# Segunda seccion 
## Funcionalidades de multimetro digital, Osciloscopio, Fuente de alimentacion de laboratorio

## Multimetro Digital
Multímetro Digital se utiliza para medir magnitudes eléctricas como:Voltaje (V)Corriente (A)Resistencia (Ω)ContinuidadFrecuencia o diodosEs esencial para verificar circuitos eléctricos o electrónicos.


<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/eb4501cc-b64c-4d85-a2eb-60e2ec5e74fb" />





## Osciloscopio 

Osciloscopio Permite visualizar señales eléctricas en gráficos temporales, mostrando:Forma de la señalFrecuenciaAmplitud del voltajeRuido en la señalIdeal para analizar cambios en señales eléctricas dentro de un circuito.



<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/1fb19a79-f6f9-405d-80e9-c29dbefdaf04" />






## Fuente de Alimentación de Laboratorio 
Fuente de Alimentación de Laboratorio Proporciona voltaje y corriente regulados a un circuito, siendo útil para:Suministrar energía eléctrica reguladaAjustar parámetros según el circuitoAlimentar prototipos o pruebas electrónicasFacilita la prueba de circuitos sin necesidad de baterías.



<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/0108ea17-3b5d-4d9d-bdaa-b7582f9e226b" />
