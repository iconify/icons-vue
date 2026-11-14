<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qob-g5brz"/><path class="ix2f4s1as"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cave-interior" /></template>
<style>
.ix2f4s1as {
  d: path("M8 5.25L9.5 9.5L11 4m2 0l1.5 5.5L16 5.25");
}

.qob-g5brz {
  d: path("M2.5 20.5h19M5 20.5V11a7 7 0 0 1 14 0v9.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
