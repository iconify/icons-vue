<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="l5g864bjc"/><path class="iuizs4b8v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dehumidifier-sharp" /></template>
<style>
.iuizs4b8v {
  d: path("M12 6.5c-1.5 1.75-2.75 3.25-2.75 4.75a2.75 2.75 0 0 0 5.5 0c0-1.5-1.25-3-2.75-4.75Zm-3.75 11h7.5");
}

.l5g864bjc {
  d: path("M5.25 2.75h13.5v18.5H5.25z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
