<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="wv5f_1brg"/><path class="hfcuht4zu"/><path class="ssqxbu1ye"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:arm-sling-sharp" /></template>
<style>
.hfcuht4zu {
  d: path("M3.25 21.25v-5.5a5 5 0 0 1 5-5h7.5a5 5 0 0 1 5 5v5.5Zm7.25-7.5h6.75");
}

.ssqxbu1ye {
  d: path("M6.75 16.75H18.5l-.77.99l-1.96 2.52l-.77.99H9l-.77-.99l-1.96-2.52l-.77-.99zm-.75 0l3.75-6");
}

.wv5f_1brg {
  cx: 12px;
  cy: 5.25px;
  r: 2.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
