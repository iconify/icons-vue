<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hrvllfc7h"/><path class="i7iu11bqr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gargoyle" /></template>
<style>
.hrvllfc7h {
  d: path("M7 12L3.5 7L8 8L6.5 2.5l4 4h3l4-4L16 8l4.5-1l-3.5 5v2q0 5-5 5t-5-5Zm-2 9.75h14M10 11h.01M14 11h.01");
}

.i7iu11bqr {
  d: path("M9.5 14h5q0 2.5-2.5 2.5T9.5 14Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
