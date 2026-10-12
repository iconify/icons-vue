<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="gp0egaclj"/><path class="qxe3_nxau"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:breathing-exercise-sharp" /></template>
<style>
.gp0egaclj {
  cx: 12px;
  cy: 12px;
  r: 3px;
}

.qxe3_nxau {
  d: path("M17.83 13.4a6 6 0 0 1-4.43 4.43m-2.8 0a6 6 0 0 1-4.43-4.43m0-2.8a6 6 0 0 1 4.43-4.43m2.8 0a6 6 0 0 1 4.43 4.43m2.56 5.3a9.25 9.25 0 0 1-4.49 4.49m-7.8 0a9.25 9.25 0 0 1-4.49-4.49m0-7.8A9.25 9.25 0 0 1 8.1 3.61m7.8 0a9.25 9.25 0 0 1 4.49 4.49");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
