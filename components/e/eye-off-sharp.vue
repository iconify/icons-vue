<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="pjpxcsbxg"/><circle class="gp0egaclj"/><path class="w6bu-4sfe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:eye-off-sharp" /></template>
<style>
.gp0egaclj {
  cx: 12px;
  cy: 12px;
  r: 3px;
}

.pjpxcsbxg {
  d: path("M2.75 12c1.9-4.1 5.3-6.75 9.25-6.75S19.35 7.9 21.25 12c-1.9 4.1-5.3 6.75-9.25 6.75S4.65 16.1 2.75 12Z");
}

.w6bu-4sfe {
  d: path("m3.75 3.75l16.5 16.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
