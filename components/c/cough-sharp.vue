<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="ohw45dbbb"/><path class="j5vd_tbex"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cough-sharp" /></template>
<style>
.j5vd_tbex {
  d: path("M6 10.25h1.75m2.5 0H12m-3 3a1 1 0 1 1 0 2a1 1 0 1 1 0-2Zm8-3.5L19.551 12L17 14.25m2-6a5.25 5.25 0 0 1 0 7.5");
}

.ohw45dbbb {
  cx: 9px;
  cy: 12px;
  r: 6.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
