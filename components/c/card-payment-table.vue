<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ut8194bgs"/><path class="y2iolbczp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:card-payment-table" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ut8194bgs {
  d: path("M3.5 8.75h17v13h-17Zm5 0l-1-5L16.25 2l1.25 6.75");
}

.y2iolbczp {
  d: path("M6.5 11.5h11v4h-11Zm2 7.25h.01m3.49 0h.01m3.49 0h.01");
}

</style>
