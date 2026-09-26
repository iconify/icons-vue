<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="qucdtki2c"/><path class="ysdtivubw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-diagram-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qucdtki2c {
  fill: currentColor;
  d: path("M3 2L21 2C21.5523 2 22 2.4477 22 3L22 8C22 8.5523 21.5523 9 21 9L3 9C2.4477 9 2 8.5523 2 8L2 3C2 2.4477 2.4477 2 3 2ZM3 15L10 15C10.5523 15 11 15.4477 11 16L11 21C11 21.5523 10.5523 22 10 22L3 22C2.4477 22 2 21.5523 2 21L2 16C2 15.4477 2.4477 15 3 15ZM14 15L21 15C21.5523 15 22 15.4477 22 16L22 21C22 21.5523 21.5523 22 21 22L14 22C13.4477 22 13 21.5523 13 21L13 16C13 15.4477 13.4477 15 14 15Z");
  stroke: none;
}

.ysdtivubw {
  d: path("M12 8L12 12M6.5 16L6.5 12L17.5 12L17.5 16");
}

</style>
