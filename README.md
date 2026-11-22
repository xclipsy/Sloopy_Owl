<div align="center">

<img width="120" height="120" alt="playstore_icon_512x512" src="https://github.com/user-attachments/assets/5868862e-7564-475d-8723-089887843e10" />

# SloopyOwl

**La alarma que te despierta cuando llegas, no cuando tú lo recuerdas.**

[![Beta publica](https://img.shields.io/badge/Beta-Pública-8E43D9?style=for-the-badge&logo=android&logoColor=white)](https://github.com/xclipsy/Sloopy_Owl/releases/tag/public-beta)
[![Android](https://img.shields.io/badge/Android-6.0+-5E17A6?style=for-the-badge&logo=android&logoColor=white)](https://github.com/xclipsy/Sloopy_Owl/releases/tag/public-beta)
[![Version](https://img.shields.io/badge/Versión-0.1.0-F2AE2E?style=for-the-badge)](https://github.com/xclipsy/Sloopy_Owl/releases/tag/public-beta)

<br/>

<a href="https://github.com/xclipsy/Sloopy_Owl/releases/tag/public-beta">
  <img src="https://img.shields.io/badge/⬇️%20Descargar%20APK-SloopyOwl%20v0.1.0%20Beta-5E17A6?style=for-the-badge&logoColor=white" alt="Descargar APK" height="50"/>
</a>

<br/><br/>

> **Beta pública** — Esta versión está en desarrollo activo. Si encuentras un problema, [abre un issue](https://github.com/xclipsy/Sloopy_Owl/issues).

</div>

---

## ¿Qué es SloopyOwl?

¿Alguna vez te has quedado dormido en el bus o el metro y pasaste tu parada? **SloopyOwl** es una aplicación Android que monitorea tu ubicación GPS en tiempo real y, cuando entras al radio que tú definiste alrededor de tu destino, **te despierta mediante vibración**, sin importar si tienes la pantalla apagada.

Perfecta para:

- 🚌 Viajeros en bus o metro que se quedan dormidos
- 🎧 Personas escuchando música con los ojos cerrados
- 💤 Cualquiera que necesite despertarse antes de llegar, no después

---

## Capturas de pantalla

<div align="center">

<table>
  <tr>
    <td align="center">
      "<img width="220" alt="device_live_check" src="https://github.com/user-attachments/assets/3ff5b690-5626-44bd-a703-1caf17011762" /><br/>
      <sub><b>Selecciona tu destino</b></sub>
    </td>
    <td align="center">
      <img width="220" alt="startup_battery_dialog" src="https://github.com/user-attachments/assets/e3a67220-969b-402a-9d0f-abcba319a761" /><br/>
      <sub><b>Configuración guiada</b></sub>
    </td>
  </tr>
</table>

</div>

---

## Cómo funciona

```
1. Abre la app  →  2. Busca tu destino  →  3. Elige el radio de alerta
        ↓
4. Cierra la pantalla y duerme tranquilo
        ↓
5. SloopyOwl vibra cuando estás cerca 🦉
```

---

## Funcionalidades

| Característica | Detalle |
|---|---|
| 🗺️ **Mapa interactivo** | Basado en OpenStreetMap, funciona sin conexión tras descargar tu ciudad |
| 📍 **Radio personalizable** | 500 m, 750 m o 1 km según tu necesidad |
| 📳 **Vibración con pantalla apagada** | GPS continuo incluso en modo ahorro sin batching |
| ⭐ **Favoritos** | Guarda tus destinos frecuentes para acceder rápido |
| 🔔 **Avisos progresivos** | Pre-aviso suave a ~1.5 km y alarma definitiva al llegar |
| 🌙 **Sin publicidad** | Ningún dato tuyo sale del dispositivo |

---

## Instalación

> Requiere **Android 6.0 o superior**

1. Descarga el APK desde el botón de arriba o desde [Releases](https://github.com/xclipsy/Sloopy_Owl/releases/tag/public-beta).
2. En tu celular, ve a **Ajustes → Seguridad → Instalar apps de fuentes desconocidas** y actívalo.
3. Abre el archivo `.apk` descargado e instala.
4. Al abrir la app, acepta el permiso de **GPS** y desactiva el **ahorro de batería** para SloopyOwl (la app te guía paso a paso).

---

## Permisos requeridos

| Permiso | Por qué |
|---|---|
| Ubicación precisa | Para detectar cuándo entras al radio del destino |
| Ejecutar en segundo plano | Para monitorear mientras la pantalla está apagada |
| Vibración | Para la alarma de llegada |
| Sin restricción de batería | Evita que Android suspenda el GPS con la pantalla apagada |

> Ningún permiso de red es necesario para el monitoreo. La conexión solo se usa para buscar direcciones y descargar el mapa de tu ciudad una sola vez.

---

## Notas de la versión `v0.1.0-beta`

- Monitoreo GPS con pantalla apagada sin throttling
- Avisos configurables durante el trayecto (1, 2 o 3 alertas)
- Mapa offline con OpenStreetMap + MapTiler
- Búsqueda de direcciones por texto
- Favoritos persistentes
- Solicitud guiada de excepción de batería al iniciar la app

---

<div align="center">

<sub>Próximamente en Google Play · Apoya el proyecto compartiendo la app</sub>

</div>
