# ASIX-B

Apuntes y ejemplos de las sesiones de HTML y CSS. Cada apartado enlaza al
ejercicio de la sesión y a la documentación correspondiente de MDN.

## Sesión 1: primeros pasos con HTML

[Ejercicio: `mi-web`](sessions/session-01/mi-web/)

- **Etiquetas:** estructura básica (`html`, `head`, `body`, `title`, `meta`),
  encabezados (`h1`–`h6`), párrafos (`p`), enlaces (`a`) y salto de línea
  (`br`). En `truco.html` también se practican listas (`ul`, `ol`, `li`),
  imágenes (`img`) y énfasis (`b`, `i`, `em`, `strong`, `mark`).
- **Atributos:** `lang`, `charset`, `name`, `content`, `id`, `title`, `href`,
  `src`, `alt`, `type` y `start`. Los enlaces usan fragmentos como `#seccion2`
  para navegar a un elemento con ese `id`.
- **Estilos:** no hay hoja de estilos en esta sesión; se introducen elementos
  HTML y sus atributos.
- **MDN:** [elementos HTML](https://developer.mozilla.org/es/docs/Web/HTML/Element),
  [atributos globales](https://developer.mozilla.org/es/docs/Web/HTML/Global_attributes),
  [enlaces y fragmentos](https://developer.mozilla.org/es/docs/Web/HTML/Element/a#enlaces_a_elementos_de_la_p%C3%A1gina),
  [listas](https://developer.mozilla.org/es/docs/Web/HTML/Element/ol),
  [imágenes](https://developer.mozilla.org/es/docs/Web/HTML/Element/img).

## Sesión 2: HTML semántico y contenido multimedia

[Ejercicio: `hello-html5`](sessions/session-02/hello-html5/)

- **Etiquetas:** estructura semántica (`header`, `nav`, `main`, `section`,
  `aside`, `footer`), listas y enlaces; contenido multimedia con `video`,
  `audio` e `iframe`; y tablas con `table`, `thead`, `tbody`, `tfoot`, `tr`,
  `th` y `td`.
- **Atributos:** `href`, `target`, `src`, `alt`, `controls`, `autoplay`,
  `muted`, `loop`, `height`, `width`, `allow`, `allowfullscreen`,
  `referrerpolicy`, `colspan` y `border`. En `index.old.html` también se
  muestra el atributo `style` con `background-color`.
- **Estilos:** se ven estilos en línea y el comportamiento predeterminado de
  los elementos semánticos, multimedia y de tabla; todavía no hay una hoja CSS
  externa.
- **MDN:** [elementos de sección](https://developer.mozilla.org/es/docs/Web/HTML/Element#contenido_de_secci%C3%B3n),
  [video](https://developer.mozilla.org/es/docs/Web/HTML/Element/video),
  [audio](https://developer.mozilla.org/es/docs/Web/HTML/Element/audio),
  [iframe](https://developer.mozilla.org/es/docs/Web/HTML/Element/iframe),
  [tablas](https://developer.mozilla.org/es/docs/Web/HTML/Element/table),
  [atributo `style`](https://developer.mozilla.org/es/docs/Web/HTML/Global_attributes/style).

## Sesión 3: selectores y propiedades CSS

[Ejercicio: `hello-css`](sessions/session-03/hello-css/)

- **Etiquetas y atributos:** `header`, `main`, `section`, `footer`, títulos,
  párrafos, listas y enlaces; `id` y `class` identifican elementos para
  aplicarles estilos. La hoja CSS se incorpora con `link`.
- **Estilos:** selectores universales, de tipo, descendientes y de hijo
  (`ul > li > a`), selectores de `id` y clase, y pseudoclases `:hover` y
  `:active`. Se practican `color`, `background-color`, `font-family`,
  `font-size`, `font-weight` y `border`, además de unidades `px` y `rem` y la
  carga de una fuente web.
- **MDN:** [sintaxis de CSS](https://developer.mozilla.org/es/docs/Web/CSS),
  [selectores](https://developer.mozilla.org/es/docs/Web/CSS/CSS_selectors),
  [pseudoclases](https://developer.mozilla.org/es/docs/Web/CSS/Pseudo-classes),
  [color](https://developer.mozilla.org/es/docs/Web/CSS/color),
  [font-size](https://developer.mozilla.org/es/docs/Web/CSS/font-size),
  [border](https://developer.mozilla.org/es/docs/Web/CSS/border).

## Sesión 4: modelo de caja

[Ejercicio: `hello-box`](sessions/session-04/hello-box/)

- **Etiquetas y atributos:** estructura con `header`, `nav`, `main`, `section`,
  `footer`, listas, enlaces y elementos `div` y `span`; las clases `box` y
  `bola` permiten seleccionar los ejemplos.
- **Estilos:** `box-sizing`, margen (`margin-left`, `margin-block`), relleno
  (`padding`), borde, contorno (`outline`), dimensiones, `display: inline-block`,
  `cursor`, `border-radius` e imagen de fondo
  (`background-image`, `background-repeat`, `background-position`,
  `background-size`). Se incluye una hoja de reinicio con reglas globales.
- **MDN:** [modelo de caja](https://developer.mozilla.org/es/docs/Web/CSS/CSS_box_model/Introduction_to_the_CSS_box_model),
  [box-sizing](https://developer.mozilla.org/es/docs/Web/CSS/box-sizing),
  [margin](https://developer.mozilla.org/es/docs/Web/CSS/margin),
  [padding](https://developer.mozilla.org/es/docs/Web/CSS/padding),
  [outline](https://developer.mozilla.org/es/docs/Web/CSS/outline),
  [background-image](https://developer.mozilla.org/es/docs/Web/CSS/background-image),
  [display](https://developer.mozilla.org/es/docs/Web/CSS/display).

## Sesión 5: Flexbox

[Ejercicio: `hello-flex`](sessions/session-05/hello-flex/)

- **Etiquetas y atributos:** composición de una página con `header`, `nav`,
  `main`, `section`, `article`, `footer`, listas, imágenes, títulos, párrafos
  y enlaces; las clases `hero`, `catalog` y `shiny` identifican los elementos.
- **Estilos:** contenedores flexibles con `display: flex`,
  `flex-direction`, `flex-wrap`, `justify-content`, `align-items`,
  `align-self`, `gap`, `order` y `flex-grow`. También se usan bordes, colores,
  espaciado y `height: 100vh`.
- **MDN:** [conceptos básicos de Flexbox](https://developer.mozilla.org/es/docs/Web/CSS/CSS_flexible_box_layout/Basic_concepts_of_flexbox),
  [display](https://developer.mozilla.org/es/docs/Web/CSS/display),
  [flex-direction](https://developer.mozilla.org/es/docs/Web/CSS/flex-direction),
  [flex-wrap](https://developer.mozilla.org/es/docs/Web/CSS/flex-wrap),
  [justify-content](https://developer.mozilla.org/es/docs/Web/CSS/justify-content),
  [align-items](https://developer.mozilla.org/es/docs/Web/CSS/align-items),
  [gap](https://developer.mozilla.org/es/docs/Web/CSS/gap).

## Sesión 6: CSS Grid

[Ejercicio: `hello-grid`](sessions/session-06/hello-grid/)

- **Etiquetas y atributos:** estructura de página con `header`, `main`,
  `section`, `aside`, `footer` y elementos `div`; la clase `grande` identifica
  una celda. Los selectores de hijo y `:nth-child()` seleccionan elementos de
  la cuadrícula.
- **Estilos:** contenedores con `display: grid`; definición de columnas y filas
  (`grid-template-columns`, `grid-template-rows`), áreas con `grid-template-areas`
  y `grid-area`, separación con `gap`, y ubicación/tamaño de elementos con
  `grid-column`, `grid-row` y `span`. También se practican unidades `fr`,
  márgenes, relleno, colores, bordes redondeados y sombras.
- **MDN:** [conceptos básicos de Grid](https://developer.mozilla.org/es/docs/Web/CSS/CSS_grid_layout/Basic_concepts_of_grid_layout),
  [grid-template-columns](https://developer.mozilla.org/es/docs/Web/CSS/grid-template-columns),
  [grid-template-rows](https://developer.mozilla.org/es/docs/Web/CSS/grid-template-rows),
  [grid-template-areas](https://developer.mozilla.org/es/docs/Web/CSS/grid-template-areas),
  [grid-area](https://developer.mozilla.org/es/docs/Web/CSS/grid-area),
  [grid-column](https://developer.mozilla.org/es/docs/Web/CSS/grid-column),
  [grid-row](https://developer.mozilla.org/es/docs/Web/CSS/grid-row).
