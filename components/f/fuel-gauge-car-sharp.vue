<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="g0mhe_b-x"/><circle class="zur2nlbbt"/><path class="v9dutcbjj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fuel-gauge-car-sharp" /></template>
<style>
.g0mhe_b-x {
  d: path("m6.15 14.88l-1.29.75a8.25 8.25 0 1 1 14.28 0l-1.29-.75");
}

.v9dutcbjj {
  d: path("m10.79 11.18l-4.34-1.17m2.05 6.24h4v5h-4zm4 1.25h3v3.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zur2nlbbt {
  cx: 12px;
  cy: 11.5px;
  r: 1.25px;
}

</style>
