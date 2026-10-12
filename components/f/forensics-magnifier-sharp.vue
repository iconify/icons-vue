<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="y-fd6pbmc"/><path class="qx1_lqwqc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:forensics-magnifier-sharp" /></template>
<style>
.qx1_lqwqc {
  d: path("m15.75 15.75l5.5 5.5M6.5 7.75a4.5 4.5 0 0 1 7.5 0M7.75 13.5v-2.75a2.5 2.5 0 0 1 5 0v1.75m-2.5-1.75v3.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y-fd6pbmc {
  cx: 10.25px;
  cy: 10.25px;
  r: 7.5px;
}

</style>
