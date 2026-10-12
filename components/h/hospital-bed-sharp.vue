<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="gplilobog"/><circle class="akzn_2afg"/><path class="h4-4wibbe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hospital-bed-sharp" /></template>
<style>
.akzn_2afg {
  cx: 7.25px;
  cy: 11.5px;
  r: 2px;
}

.gplilobog {
  d: path("M2.75 5.5v14.75m0-4.25h18v4.25");
}

.h4-4wibbe {
  d: path("M11.75 16v-5.75h9V16M16 3.75v4.5M13.75 6h4.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
