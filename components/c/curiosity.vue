<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="es-hx3bkl"/><path class="y_381zb8x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:curiosity" /></template>
<style>
.es-hx3bkl {
  d: path("M6 16.25A8.5 7.5 0 1 1 9 18l-5 2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y_381zb8x {
  d: path("M10 8.5a2 2 0 1 1 3 1.75c-.6.35-1 .75-1 1.5m0 2.75h.01");
}

</style>
