<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="xtnw8yhak"/><path class="z65860edw"/><circle class="mxz2w86rj"/><circle class="wy0v_abdz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:karaoke-mic-sharp" /></template>
<style>
.mxz2w86rj {
  cx: 4.25px;
  cy: 9.5px;
  r: 1.25px;
}

.wy0v_abdz {
  cx: 7.75px;
  cy: 8.75px;
  r: 1.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xtnw8yhak {
  cx: 15.5px;
  cy: 8.5px;
  r: 4px;
}

.z65860edw {
  d: path("m12.12 6.88l5 5m-3.24-6.76l5 5m-7.07-.08l-8.45 8.82l1.78 1.78l8.78-8.47M5.5 9.5V3.75l3.5-1v6");
}

</style>
