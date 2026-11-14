<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="guqqttbir"/><path class="su8ir1blc"/><path class="xmjzcabdq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-settings" /></template>
<style>
.guqqttbir {
  d: path("M3.5 3v17.5h8.2");
}

.su8ir1blc {
  d: path("M6.5 14L10 8.5l3 2.5l6-6.5m-4.5 11.25h7m-7 4.5h7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xmjzcabdq {
  fill: currentColor;
  d: path("M15.5 15.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm2.5 4.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

</style>
