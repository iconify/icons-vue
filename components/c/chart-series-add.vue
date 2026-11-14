<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="guqqttbir"/><path class="ikdf4xbna"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-series-add" /></template>
<style>
.guqqttbir {
  d: path("M3.5 3v17.5h8.2");
}

.ikdf4xbna {
  d: path("M6.5 10.5c2-5.5 4-5.5 6-2s4 1.5 7-4m-13 12c2-5.5 4-5.5 6-3.5m5.5 1.5v7M14.5 18h7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
