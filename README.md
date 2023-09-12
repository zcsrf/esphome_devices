# esphome_devices
Contains the YAML for my devices

## ESM v1

This is a socket power monitor from Athom (similar to tuya and other brands).

Use this on v1 of the hardware. If measures are way off, calibration might be needed!

It is mostly a copy of the original yaml.

## ESM v2

This is a socket power monitor from Athom (similar to tuya and other brands).

Use this on v2 of the hardware. This is way more precise than v1.

It is mostly a copy of the original yaml

## Visonic

Used to integrate the Visonic alarm with Home Assistant (using serial stream), it as two relays to trigger remote alarm events.

Also used as a "Ble Tracker" for presence detection and communicate with Xiaomi HHCCJCY01 and CGG1.

## SDM 230

No longer in use!

Communicates with the SDM 230 and transmits the data.

## Dashboard

An attemp at doing a mini desk e-paper dashboard using Lilygo t5-4.7. 

On Hold.

## Garage

### Garage Desk and Fan

Using a 4 pwm output light controller we control the Brightness of the Lamp and the Air exhaust fan.

Please note that the PWM goes to the PWM pin on 4 pin fans, PWM the power pin didn't work as expected.

### Garage Multi Sensor

This is a enviromental sensor used on our garage.

It measures the following parameters:
- PM2.5 using a PM1006 from the Ikea sensor
- Temperature, Humidity and CO2 using a SCD41

It also had a initial test of a stream to connect to Pylontech battery.

## Aquarium

### Aquarium Relay

This controls 4 relays, 
Relay 1 and 3 are used for light control (Aquael LEDDY TUBE PLANT 2.0 and LEDDY TUBE SUNNY DAY&NIGHT).
Relay 4 controls the CO2.

Simply adjust the times according to your requirements.