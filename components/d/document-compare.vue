<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hncvdfs0e"/><path class="es5nztbir"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:document-compare" /></template>
<style>
.es5nztbir {
  d: path("M10.75 9.75L9 12l1.75 2.25m2.5-4.5L15 12l-1.75 2.25");
}

.hncvdfs0e {
  d: path("M4 4.5h2.5L9 7v11a1.5 1.5 0 0 1-1.5 1.5H4A1.5 1.5 0 0 1 2.5 18V6A1.5 1.5 0 0 1 4 4.5Zm12.5 0H19L21.5 7v11a1.5 1.5 0 0 1-1.5 1.5h-3.5A1.5 1.5 0 0 1 15 18V6a1.5 1.5 0 0 1 1.5-1.5ZM9 12h6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
