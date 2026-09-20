<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vddehgbmg"/><path class="ghf6zpb7j"/><path class="x0qn9gsac"/><path class="g7qu0vb4t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:confidence-score-outline-regular" /></template>
<style>
.g7qu0vb4t {
  d: path("M21 14v4");
}

.ghf6zpb7j {
  d: path("M14 12v6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vddehgbmg {
  d: path("m2 14 3 3 5 -5");
}

.x0qn9gsac {
  d: path("M17.5 8v10");
}

</style>
