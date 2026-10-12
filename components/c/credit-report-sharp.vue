<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="eifrm_8kj"/><circle class="km8emob2x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:credit-report-sharp" /></template>
<style>
.eifrm_8kj {
  d: path("M3.25 16.25a8.75 8.75 0 0 1 2.67-6.29M8.58 8.2a8.75 8.75 0 0 1 6.84 0m2.66 1.76a8.75 8.75 0 0 1 2.67 6.29m-7.51-1.24l2.3-2.3");
}

.km8emob2x {
  cx: 12px;
  cy: 16.25px;
  r: 1.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
