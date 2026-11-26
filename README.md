# Historias diarias · Fundación Ballet de Cúcuta

Una historia de Instagram por día en @fundacionballetdecucuta, a las 8:00 p. m. (hora de Colombia),
publicada por una tarea programada de Claude Code con Composio.

- `cola.json`: el calendario (una entrada por fecha; ninguna se repite).
  - `fuente: "repo"` → imagen de `img/` en este repositorio.
  - `fuente: "instagram"` → reel ya publicado en la cuenta (se toma su video con un enlace fresco ese día).
- `img/`: historias diseñadas (1080×1920).
- `video/`: las mismas historias convertidas en video de 15 s con música de ballet generada por código
  (tema de El Lago de los Cisnes de Tchaikovsky —dominio público— en arreglo propio, y valses/adagio de clase propios).
  Si un video falla, la tarea usa la imagen fija de `img/` como respaldo.
