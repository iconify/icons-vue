<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bgh6u3btj"/><path class="x3_nrabpe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:campus-map" /></template>
<style>
.bgh6u3btj {
  d: path("m3 5.5l6-2l6 2l6-2v15l-6 2l-6-2l-6 2Zm6-2v15m6-13v15");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x3_nrabpe {
  d: path("m12 9.75l.647 1.36l1.493.195l-1.094 1.035l.277 1.48L12 13.1l-1.323.72l.277-1.48l-1.094-1.035l1.493-.195Z");
}

</style>
