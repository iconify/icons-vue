<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="it_k9ghhm"/><path class="c2y_labmc"/><circle class="plcwa1btj"/><path class="hiyce_7rc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:case-lower-sharp" /></template>
<style>
.c2y_labmc {
  d: path("M10.75 11v8.25");
}

.hiyce_7rc {
  d: path("M13.75 4.75v14.5");
}

.it_k9ghhm {
  cx: 6.75px;
  cy: 15px;
  r: 4px;
}

.plcwa1btj {
  cx: 17.5px;
  cy: 15.5px;
  r: 3.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
