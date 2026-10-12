<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="i1bey_mjy"/><path class="de9ne4f9m"/><path class="y3b0-dket"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:kulfi-stick-sharp" /></template>
<style>
.de9ne4f9m {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 9h.01m2.24 2.75h.01M11.25 14h.01");
}

.i1bey_mjy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 6.5a3.75 3.75 0 0 1 7.5 0l-.8 9.5l-.093 1.154l-1.157-.004h-3.4l-1.157.004L9.05 16Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.y3b0-dket {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 17.15v4.1");
}

</style>
