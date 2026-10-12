<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="f-nnktbjr"/><path class="zdidvox5x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:camel-sharp" /></template>
<style>
.f-nnktbjr {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 14.25C3.75 9.75 6 6.5 9 6.5c2.5 0 3.75 2.25 4.75 4.75l2.25-4l.571-1h4.679V9h-2.5l-2.25 5.5l-.833 1.25H3.75zm2 1.5v5.5m2.5-5.5v5.5m4.75-5.5v5.5M15.5 15l.25 6.25");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.zdidvox5x {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.25 8.5h.01");
}

</style>
