# nodemcu-01
Blinkprogram NodeMCU
# Blinkprogram för NodeMCU (ESP8266)

## Översikt
Detta projekt visar hur man får en LED på NodeMCU att blinka med hjälp av Arduino-miljön. Målet är att ge en enkel introduktion till hur man programmerar en mikrokontroller.

## Mikroprocessor (ESP8266)
NodeMCU använder mikroprocessorn ESP8266, som är en liten men kraftfull WiFi-mikrokontroller med flera digitala I/O-pinnar. Den inbyggda LED-dioden sitter oftast på pinnen D4 (GPIO2).

## Arduino-funktionerna
Arduino-program består alltid av två huvudfunktioner:

setup() körs en gång när mikrokontrollern startar, och används för att ställa in portar och startinställningar.
loop() körs om och om igen och innehåller programmet som ska upprepas.

## Portinitialisering
För att kunna styra en LED måste pinnen först ställas in som OUTPUT. Detta görs i setup() med kommandot pinMode(LED_BUILTIN, OUTPUT).

## Kodexempel
Här är ett enkelt exempel på ett Blink-program som tänder och släcker den inbyggda LED-dioden:
<img width="498" height="225" alt="Skärmavbild 2025-11-27 kl  21 41 20" src="https://github.com/user-attachments/assets/b4b7b988-716f-446a-9c8e-d6b4db908892" />


## Bild
Här är en bild på en NodeMCU-modul så att du ser hur den ser ut:
