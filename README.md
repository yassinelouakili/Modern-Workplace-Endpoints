# Modern Workplace Endpoints

Proyecto práctico de portfolio orientado a consolidar conocimientos básicos de **Microsoft 365, identidad, gestión de dispositivos, seguridad de endpoints, aplicaciones y automatización**.

El proyecto se desarrolla en un entorno de laboratorio utilizando **Microsoft Entra ID** y **Microsoft Intune**, documentando las configuraciones realizadas y las comprobaciones necesarias para entender cómo funciona cada parte del entorno.

## Objetivo

Crear y documentar un entorno de **gestión moderna de dispositivos** paso a paso.

El proyecto incluye tareas relacionadas con:

* Gestión de usuarios, grupos y roles.
* Configuración de identidad y licencias.
* Enrolamiento y configuración de dispositivos.
* Aplicación de medidas básicas de seguridad.
* Despliegue y gestión de aplicaciones.
* Automatización de tareas mediante PowerShell y Microsoft Graph.
* Consultas y reporting mediante KQL.
* Administración de diferentes servicios de Microsoft 365.

La idea es que cada tarea quede **configurada, probada y documentada**, incluyendo evidencias que permitan comprobar que funciona correctamente.

## Entorno

* Microsoft 365 E5 Developer
* Microsoft Entra ID
* Microsoft Intune
* PowerShell + Microsoft Graph
* KQL (consultas de dispositivos / reporting)

## Estructura

```
modern-workplace-endpoints
├── README.md
├── 01-identidad-infraestructura/      # usuarios, roles y grupos en Entra ID, licenciamiento
├── 02-gestion-dispositivos/           # enrolamiento, Autopilot, perfiles de configuración
├── 03-seguridad-endpoint/             # antivirus, firewall, ASR, BitLocker, Defender for Endpoint
├── 04-gestion-aplicaciones/           # despliegue de apps, políticas de protección y configuración
├── 05-automatizacion-monitorizacion/  # automatización con PowerShell/Graph, KQL, Endpoint Analytics, reporting
└── 06-colaboracion-m365/              # Exchange Online, grupos M365, SharePoint/OneDrive, Teams
```

Cada carpeta numerada contiene:

* `README.md` - explica el objetivo de la práctica, qué se configuró y cómo se comprobó.
* `scripts/` - scripts de PowerShell, Microsoft Graph o consultas KQL utilizadas.
* `evidence/` - capturas o exportaciones utilizadas para demostrar las comprobaciones realizadas.

## Estado

**[En progreso]**
