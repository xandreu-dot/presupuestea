# Guía de usuario de Presupuestea

Esta guía explica, paso a paso, cómo usar la app. No hace falta saber nada de informática.

## 1. Instalar

### En Windows

1. Entra en la página de descarga: **github.com/xandreu-dot/presupuestea** y pulsa **Descargar para Windows**.
2. En la página que se abre, haz clic en el archivo **Instalar-Presupuestea-….exe** (apartado *Assets*). Se guarda en tu carpeta **Descargas**.
3. Abre el archivo con doble clic.
4. Si Windows muestra **«Windows protegió su PC»**, pulsa **Más información** y después **Ejecutar de todas formas**. Sale porque el programa todavía no tiene firma digital; es normal.
5. Pulsa **Siguiente → Instalar → Finalizar**. No hace falta ser administrador.

La app se abre en tu navegador (Chrome, Edge…). Desde entonces la abres con el icono **Presupuestea** del Escritorio o del menú Inicio.

### En Mac

1. En la página de descarga, descarga la versión de tu Mac. Para saber cuál es: menú  › **Acerca de este Mac**.
   - Si pone **Chip Apple M1, M2, M3…**: descarga **Presupuestea-…-Mac-AppleSilicon.dmg**.
   - Si pone **Procesador Intel**: descarga **Presupuestea-…-Mac-Intel.dmg**.
   - Necesitas macOS 14 o posterior (chip Apple) o macOS 15 o posterior (Intel): lo ves en la misma ventana.
2. Abre el archivo descargado y **arrastra el icono de Presupuestea a la carpeta Aplicaciones**.
3. Abre **Aplicaciones** y haz doble clic en **Presupuestea**. La primera vez el Mac dirá que **no ha podido verificar** la app (todavía no tiene firma de Apple; es normal). Pulsa **Hecho**.
4. Abre **Ajustes del Sistema › Privacidad y seguridad**, baja hasta el final y, donde pone que se ha bloqueado «Presupuestea», pulsa **Abrir igualmente**. Confirma con tu contraseña o Touch ID.
5. A partir de entonces se abre normalmente desde **Aplicaciones** o el Dock.

**Para cerrarla** (Windows y Mac), pulsa **⏻ Cerrar la app** abajo en el menú de la izquierda. Cerrar la pestaña del navegador no la detiene.

## 2. Primer uso: el asistente

La primera vez se abre un asistente de unos 3 minutos:

1. **Nombre del espacio.** Un *espacio* es un presupuesto con sus cuentas y sus datos (por ejemplo, «Familia García»). Puedes tener varios y nunca se mezclan.
2. **Tus cuentas.** Elige el banco de cada cuenta y, si quieres, ponle un alias («Gastos casa»). Marca **efectivo** si también quieres apuntar lo que pagas en metálico.
3. **Categorías.** Elige la **plantilla para el hogar** (recomendada): ya trae categorías como *Gastos fijos › Supermercado* y reglas que reconocen los comercios más habituales.
4. **IA (opcional).** Ver el apartado 8. Puedes pulsar **Ahora no** y activarla más tarde.
5. **¡Listo!** Pulsa **Importar mis movimientos**.

Para crear otro espacio más adelante: **⇄ Cambiar de espacio › Crear un espacio nuevo**.

## 3. Traer tus movimientos

### Opción A: con el extracto del banco

1. Entra en la web de tu banco y descarga los movimientos en **Excel o CSV**:
   - **Banco Sabadell**: consulta de movimientos › exportar a Excel.
   - **CaixaBank**: movimientos › descargar en Excel (simple o ampliado).
   - **Revolut**: extracto › formato **CSV**.
2. En la app, ve a **Importar extractos** y arrastra el archivo (o varios a la vez) a la zona de carga, o pulsa **Elegir archivos**.
3. La app reconoce el banco y la cuenta sola, y **descarta los movimientos repetidos**: puedes importar extractos que se solapen sin miedo.

Por ahora la app lee los extractos de **Banco Sabadell, CaixaBank y Revolut**. Para otros bancos, usa la opción B.

### Opción B: conexión directa con el banco (avanzado)

Los movimientos llegan solos cada vez que abres la app. Requiere darse de alta (gratis, para tus propias cuentas) en **Enable Banking**, un proveedor autorizado de banca abierta. La app incluye la guía completa en **Ajustes › Conexión bancaria**. Después, en **Importar extractos › Bancos conectados**, pulsa **Conectar** en cada cuenta y autoriza el acceso en la web de tu banco. Cada 90–180 días el banco pide renovar el permiso; la app te avisa con una **«!»** en el menú.

## 4. Revisar los pendientes

Todo movimiento nuevo entra en **Pendientes** con una **propuesta** de categoría y subcategoría.

- Si la propuesta es correcta, pulsa **✓** en la línea (o **Aprobar confianza alta** / **Aprobar todo** para muchas a la vez).
- Si no, cámbiala en los desplegables **Categoría** y **Subcategoría** y aprueba.
- **⊘** marca un movimiento para que **no compute** (por ejemplo, un traspaso entre tus cuentas o un reembolso de un amigo). Desaparece de Pendientes.
- **✂** divide un movimiento en varias categorías (por ejemplo, una compra con parte de casa y parte de ocio).
- **⚑** crea una **regla**: la próxima vez ese concepto se clasificará solo.

**Cuantos más movimientos apruebes, mejor acertará la app**: aprende de cada decisión. Puedes ordenar la lista pulsando en cualquier encabezado.

## 5. Cargar el presupuesto

1. Ve a **Presupuesto** y pulsa **⇩ Descargar plantilla** del año.
2. Abre el Excel y escribe cuánto prevés gastar cada mes en cada categoría (deja en blanco lo que no quieras presupuestar). Si escribes una categoría nueva, se creará sola.
3. Guarda el archivo y pulsa **⇪ Cargar Excel**.

Puedes cargar versiones nuevas cuando quieras; la última queda activa.

## 6. Cuadro de mando

Muestra, por mes o acumulado en el año, lo **gastado frente a lo presupuestado** por categoría, con un semáforo:

- **Verde**: dentro del presupuesto o con una desviación pequeña.
- **Ámbar**: desviación moderada.
- **Rojo**: desviación importante. El umbral se cambia en **Ajustes**.

Solo cuentan los movimientos **aprobados** y que **computan**. Los traspasos entre cuentas no cuentan como gasto ni como ingreso.

## 7. Efectivo, todos los datos, espacios y actas

- **Efectivo**: apunta los pagos en metálico. Si sacas dinero del cajero, regístralo como **Entrada** con la categoría **Traspaso entre cuentas** para no contarlo dos veces.
- **Todos los datos**: todos los movimientos (los que computan, los excluidos y los pendientes), con filtros y **⇩ Exportar a Excel**.
- **Categorías y reglas**: crea, renombra o desactiva categorías y gestiona las reglas automáticas.
- **Actas**: anota las reuniones de seguimiento del presupuesto (decisiones y acciones) y guárdalas en PDF con **⎙ Imprimir / PDF**.
- **Ajustes**: nombre del espacio, cuentas y alias, umbral de desviación, IA y conexión bancaria.

## 8. IA en tu ordenador (opcional)

La app puede usar una inteligencia artificial que **funciona dentro de tu ordenador** (nada sale de él) para proponer la categoría de comercios que nunca has clasificado.

1. Instala **Ollama** (gratuito) desde **ollama.com/download** (hay versión para Windows y para Mac) y ábrelo.
2. En el asistente (o al crear un espacio nuevo), pulsa **Descargar el modelo**. Son unos 5 GB y puede tardar entre 10 y 30 minutos.

Se recomienda un ordenador con 16 GB de memoria. Si Ollama no está abierto, la app funciona igual, sin IA.

## 9. Copias, desinstalar y problemas frecuentes

- **Dónde están mis datos**: en Windows, en la carpeta `%LOCALAPPDATA%\Presupuestea\datos`; en Mac, en `~/Library/Application Support/Presupuestea/datos`. Cada vez que abres la app se guarda una copia de seguridad automática (se conservan las 30 últimas).
- **Copia manual**: cierra la app y copia esa carpeta a un disco externo o a tu nube.
- **Desinstalar**: en Windows, *Configuración › Aplicaciones › Aplicaciones instaladas › Presupuestea › Desinstalar*; en Mac, arrastra **Presupuestea** de **Aplicaciones** a la Papelera. Tus datos **no se borran**.

**Problemas frecuentes**

- *No se abre la app*: espera unos segundos (la primera vez tarda más). Si sigue sin abrirse, reinicia el ordenador y vuelve a probar.
- *En Mac dice que la app «está dañada»*: pasa a veces con programas sin firma de Apple. Abre la app **Terminal**, pega `xattr -cr /Applications/Presupuestea.app`, pulsa Intro y vuelve a abrirla.
- *«El puerto 8770 lo está usando otro programa»*: cierra el otro programa o reinicia el ordenador.
- *Un extracto da error*: comprueba que es de Banco Sabadell, CaixaBank o Revolut y que lo has descargado en Excel o CSV.
- *La IA no propone nada*: comprueba en **Ajustes** que Ollama está en marcha y el modelo descargado.
- *Otra duda o un error*: abre una incidencia en **github.com/xandreu-dot/presupuestea/issues**. No incluyas datos personales ni capturas con tus movimientos: la página es pública.
