<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="l8q_rz2xm"/><circle class="pei_pcr2y"/><path class="fwxo20bai"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:air-purifier-sharp" /></template>
<style>
.fwxo20bai {
  d: path("M7.75 3.5c1.4 1 2.85-1 4.25 0l2.125 1.518L16.25 3.5m-8.5 3c1.4 1 2.85-1 4.25 0l2.125 1.518L16.25 6.5");
}

.l8q_rz2xm {
  d: path("M5.75 9.5h12.5v11.75H5.75z");
}

.pei_pcr2y {
  cx: 12px;
  cy: 15.375px;
  r: 2.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
