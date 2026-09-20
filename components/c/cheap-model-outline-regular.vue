<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n6qz8-ogr"/><path class="mc3x0bbgo"/><path class="fxkurobsu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cheap-model-outline-regular" /></template>
<style>
.fxkurobsu {
  d: path("M17.5 10.5v3");
}

.mc3x0bbgo {
  d: path("M13 12a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

.n6qz8-ogr {
  d: path("M6.5 8.5 10 12l-3.5 3.5L3 12Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
