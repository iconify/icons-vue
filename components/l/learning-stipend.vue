<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nutn4acqi"/><path class="pu22_cc-y"/><path class="qbynkn2mn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:learning-stipend" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nutn4acqi {
  d: path("M7.375 10h9.25A4.375 4.375 0 0 1 21 14.375v2.75a4.375 4.375 0 0 1-4.375 4.375h-9.25A4.375 4.375 0 0 1 3 17.125v-2.75A4.375 4.375 0 0 1 7.375 10");
}

.pu22_cc-y {
  d: path("M21 13.25h-3.5a2 2 0 0 0 0 4H21M5.5 10V4A1.5 1.5 0 0 1 7 2.5h10.5V10M8 2.5V10");
}

.qbynkn2mn {
  d: path("M12 2.5V7l1.25-1l1.25 1V2.5");
}

</style>
