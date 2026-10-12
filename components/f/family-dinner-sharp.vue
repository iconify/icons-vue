<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="ryglc3byv"/><circle class="xlifx1bjg"/><path class="q5ardcbsw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:family-dinner-sharp" /></template>
<style>
.q5ardcbsw {
  d: path("M4.5 13.5h6a3 3 0 0 1-6 0Zm9 0h6a3 3 0 0 1-6 0Zm-10.75 6h18.5");
}

.ryglc3byv {
  cx: 7.5px;
  cy: 7px;
  r: 2.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xlifx1bjg {
  cx: 16.5px;
  cy: 7px;
  r: 2.25px;
}

</style>
