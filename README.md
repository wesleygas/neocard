# neocard
A VHDL peripheral for controling neopixels (WS281X ALEDs). 

The color data is continuously read from a on-chip memory (VRAM equivalent) and exposed via a glue-logic component to the Avalon Bus.

A complete guide on how to implement this on the Altera FPGA DE10-Standard development board and how to integrate it onto a linux driver 
is available at (in Portuguese):


- Hardware(: https://insper.github.io/Embarcados-Avancados/2020/LED-HW/
- Software (Linux driver): https://insper.github.io/Embarcados-Avancados/2020/LED-Linux/

