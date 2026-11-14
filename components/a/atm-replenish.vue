<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m8-zy9bhl"/><path class="bo1jmldxz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:atm-replenish" /></template>
<style>
.bo1jmldxz {
  d: path("M13.5 7a2 1.25 0 1 0 4 0a2 1.25 0 1 0-4 0Zm-8 9.75h5M18 21v-6m-2.5 2.5L18 15l2.5 2.5");
}

.m8-zy9bhl {
  d: path("M15.2 21.5H2.5V12h14.6m1.8 0h2.6v2.6m0 5.8v1.1h-.7M4 12V6.5a1 1 0 0 1 1-1h2.5m0 6.5V5a1 1 0 0 1 1-1H11m0 8V3.5a1 1 0 0 1 1-1h7a1 1 0 0 1 1 1V12");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
