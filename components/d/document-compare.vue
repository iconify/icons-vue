<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jtygabc8p"/><path class="es5nztbir"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:document-compare" /></template>
<style>
.es5nztbir {
  d: path("M10.75 9.75L9 12l1.75 2.25m2.5-4.5L15 12l-1.75 2.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jtygabc8p {
  d: path("M4 4.5h2.5L9 7v11a1.5 1.5 0 0 1-1.5 1.5H4A1.5 1.5 0 0 1 2.5 18V6A1.5 1.5 0 0 1 4 4.5m12.5 0H19L21.5 7v11a1.5 1.5 0 0 1-1.5 1.5h-3.5A1.5 1.5 0 0 1 15 18V6a1.5 1.5 0 0 1 1.5-1.5M9 12h6");
}

</style>
