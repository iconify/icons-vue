<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cafe3oq2n"/><path class="g-mrv1hbe"/><path class="i7xbhqbba"/><path class="ra24a3r4r"/><path class="vddehgbmg"/><path class="ghf6zpb7j"/><path class="x0qn9gsac"/><path class="g7qu0vb4t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:confidence-score-duotone-regular" /></template>
<style>
.cafe3oq2n {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m2 14 3 3 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g-mrv1hbe {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 12v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g7qu0vb4t {
  d: path("M21 14v4");
}

.ghf6zpb7j {
  d: path("M14 12v6");
}

.i7xbhqbba {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17.5 8v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ra24a3r4r {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M21 14v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vddehgbmg {
  d: path("m2 14 3 3 5 -5");
}

.x0qn9gsac {
  d: path("M17.5 8v10");
}

</style>
