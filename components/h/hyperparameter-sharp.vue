<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="wbz5lyb3q"/><circle class="elerq_bpn"/><circle class="res1f5h-j"/><path class="nlg4d8b7s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hyperparameter-sharp" /></template>
<style>
.elerq_bpn {
  cx: 5.5px;
  cy: 8.75px;
  r: 2.5px;
}

.nlg4d8b7s {
  d: path("M18.25 6.75L14.5 11.5h3.25L17 14.75L20.75 10H18z");
}

.res1f5h-j {
  cx: 11px;
  cy: 15.75px;
  r: 2.5px;
}

.wbz5lyb3q {
  d: path("M5.5 2.75v3.5m0 5v10M11 2.75v10.5m0 5v3");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
