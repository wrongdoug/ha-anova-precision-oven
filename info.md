## Anova Precision Oven

Home Assistant integration for the Anova Precision Oven (APO) using Anova's [official developer API](https://developer.anovaculinary.com/docs/devices/wifi/oven-commands). Real-time telemetry via WebSocket plus basic control (on/off, target temperature, lamp).

> **Provided as-is. No warranty. No expectation of maintenance, support, or future updates.**

**Supported:** Anova Precision Oven v1 (tested), v2 (untested, reads likely work).
**Not supported:** Anova Precision Cooker (APC sous vide) -- use the built-in `anova` integration in HA core.

### Entities

- 17 sensors: temperatures, humidity, timer, mode, setpoints, fan speed, heating elements, probe, cook session, firmware
- 4 binary sensors: connectivity, door, water tank, vent
- 1 climate: simple single-stage dry cook start/stop (see README for caveats)
- 1 switch: lamp

### Requirements

Anova Personal Access Token (starts with `anova-`) from the Anova developer portal.
