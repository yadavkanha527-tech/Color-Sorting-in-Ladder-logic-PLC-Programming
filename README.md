
# Color Sorting in Ladder Logic – PLC Programming

# Automatisierte Farbsortieranlage mit SPS

## Projektbeschreibung

In diesem Projekt wurde eine automatisierte Farbsortieranlage mit CODESYS und Factory I/O entwickelt und simuliert.

Die Anlage erkennt mithilfe eines Vision-Sensors zwei verschiedene Farben (Blau und Grün) und sortiert die Objekte automatisch über ein Förderbandsystem.

## Verwendete Software und Technologien

- CODESYS
- Factory I/O
- OPC Client DA/UA

## Funktionen

- Automatischer Förderbandbetrieb
- Farberkennung mithilfe eines Vision-Sensors
- SPS-gesteuerte Sortierung
- Automatische Trennung der Objekte nach Farben (Blau und Grün)
- Not-Halt-Funktion über einen Not-Halt-Taster

## Projektstruktur

- `CODESYS/` – SPS-Programm und globale Variablen
- `FactoryIO/` – Simulationsdatei der Anlage
- `Images/` – Screenshots des Projekts
- `Videos/` – Demonstration der Anlage

## Lernziele

Ziel dieses Projekts ist es, grundlegende Kenntnisse der industriellen Automatisierung und SPS-Programmierung praktisch anzuwenden und zu vertiefen.

Insbesondere wurden folgende Grundlagen der SPS-Programmierung geübt:

- Verriegelungen
- Setz- und Rücksetzfunktionen (SR/RS)
- Zähler (Counter)
- Zeitglieder (Timer)
- Merker (Flags)

## Bekannte Probleme / Einschränkungen

- Gelegentlich reagiert der photoelektrische Sensor am Ausgang nicht zuverlässig.

## Autor

Krishna Yadav
