# Capturas para la presentación beta

**Estado: 14 listas · 12 pendientes.** El bloque de cliente ya está completo (las dos que faltaban —barra de carga y racha— se sacaron de la presentación). Lo que queda son 12 capturas entre instructor, administrador y diferenciadores.

- **Dónde guardarlas:** en la carpeta `img/`, junto a `index.html`.
- **Nombre exacto:** el de la columna *Archivo*. La presentación ya apunta a ese nombre; en cuanto pongas el archivo, aparece sola (basta recargar el navegador).
- **Formato:** JPG, calidad alta (≥ 90) — sobre todo en las de escritorio, que tienen texto fino.
- **Tema:** todo en **modo oscuro**.
- **Recorte:** los marcos recortan desde **arriba**, así que encuadra lo importante en la parte superior. No hace falta que recortes tú.

**Cómo capturar:**

| Tipo | Cómo | Proporción |
|---|---|---|
| 📱 **Teléfono** | Simulador de iPhone (⌘S), o Chrome → DevTools → modo dispositivo a 390 × 844 | vertical, ~9:19.5 |
| 💻 **Escritorio** | Ventana del navegador a ~1440 × 900, sin barra de marcadores | horizontal, ~16:10 |

---

## ⏳ Pendientes (12)

### Instructor — 4

| # | Archivo | Dónde | Qué tiene que mostrar |
|---|---|---|---|
| 17 | `17_instructor_dashboard.jpg` | 📱 `/dashboard` (rol instructor) | El panel del instructor: saludo, los KPIs (**Próximas clases**, **Clases dictadas**, **Asistencia promedio** con el gauge) y las próximas clases que dicta. |
| 19 | `19_instructor_widget_vivo.jpg` | 📱 `/dashboard` **mientras dicta una clase** | ⭐ La más importante del bloque. El widget en vivo con el **roster**: cada alumno con su avance (**"8/12 series · 67 %"**). Que se vean varios alumnos con progresos distintos. |
| 21 | `21_instructor_alumnos.jpg` | 📱 `/students` | La lista de alumnos. Si hay alguno **en riesgo**, que se vea la marca. |
| 23 | `23_instructor_estadisticas.jpg` | 💻 `/stats` → **Como instructor** | Sus números: ocupación, no-show, retención y el **radar**. |

### Administrador — 4

| # | Archivo | Dónde | Qué tiene que mostrar |
|---|---|---|---|
| 24 | `24_admin_dashboard.jpg` | 💻 `/dashboard` (rol admin) | El panel completo: los KPIs arriba (**Miembros activos**, **Reservas hoy**, **Ingresos del mes**), las clases de hoy y las alertas de vencimiento. |
| 25 | `25_admin_sesiones_vivo.jpg` | 💻 `/dashboard` **con clases corriendo** | ⭐ El widget **multi-sesión**: los chips de las clases en vivo y una abierta con su roster. Con dos clases solapadas se luce; **con una basta**. |
| 28 | `28_admin_importacion.jpg` | 💻 `/import` | ⭐ **El paso de mapeo de columnas** (no el de subir el archivo): la app reconociendo las columnas de una planilla ajena y la asignación de planes. Es la captura que vende la migración. |
| 29 | `29_admin_estadisticas.jpg` | 💻 `/stats` → **Resumen** o **Año** | La vista con más gráficos. Si el gráfico del **Año** (contra el año anterior) tiene datos, úsalo: es el más impresionante. |

### Lo que nos distingue — 4

| # | Archivo | Dónde | Qué tiene que mostrar |
|---|---|---|---|
| 31 | `31_paleta_gimnasio_a.jpg` | 📱 `/dashboard` con la paleta **Teal** | El panel del cliente, en teal. |
| 32 | `32_paleta_gimnasio_b.jpg` | 📱 `/dashboard` con otra paleta (**Loica**, **Flamenco** o **Cometocino**) | ⚠️ **El mismo encuadre exacto** que la 31, con otro color. Toma las dos seguidas, sin scrollear entremedio: la gracia es que se vea que cambia la app entera, no el logo. |
| 34 | `34_ia_chat_app.jpg` | 📱 el botón ✨ flotante | Una conversación real. Lo ideal: una respuesta con **tarjetas o un mini-gráfico con color**, o la **tarjeta de confirmación de reserva** ("consume 1 crédito · te quedarán 3"). |
| 35 | `35_ia_whatsapp.jpg` | 📱 WhatsApp | Una conversación con el bot desde WhatsApp de verdad. |

> **Truco:** la 19, la 25 y (si la haces con dos clases) el widget multi-sesión necesitan **una clase corriendo en ese momento**. Prepara una sesión de prueba que caiga sobre la hora actual y saca las tres de corrido: instructor primero, admin después.

---

## ✅ Ya están (14)

`01_cliente_dashboard` · `02_cliente_reservar_horario` · `03_cliente_reserva_detalle` · `04_cliente_widget_vivo_colapsado` · `05_cliente_widget_vivo_expandido` · `07_cliente_rutina_completa` · `08_rutina_bloques` · `09_ejercicio_video` · `10_cliente_progreso` · `11_cliente_records` · `12_cliente_logros` · `14_cliente_novedades` · `15_cliente_encuesta` · `16_cliente_membresia`

## 🗑 Sacadas de la presentación

Estas ya no se usan; **no hay que sacarlas**:

| Era | Por qué se sacó |
|---|---|
| `06_cliente_barra_carga` | La barra de carga ya se dibuja **en vivo con CSS** en esa diapositiva, así que la captura era redundante. |
| `13_cliente_racha` | La racha ya se ve en el panel (captura 01). |
| `18_instructor_mis_clases` · `20_instructor_registro_alumno` · `22_instructor_alumno_detalle` | Recorte de volumen: el panel (17) y el widget en vivo (19) cuentan la misma historia. |
| `26_admin_sesiones` · `27_admin_pagos` · `30_admin_configuracion` | Esas tres diapositivas se rehicieron **como tarjetas de texto**, sin captura. |
| `33_paleta_editor` · `36_nativo_ios` · `37_modo_claro` | La diapositiva de paletas ya muestra los 12 colores dibujados en vivo; la de "app nativa" pasó a tarjetas. |
