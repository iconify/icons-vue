<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z0f71wboc"/><path class="vtfu0drzm"/><path class="bvu0653wk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:atm-cash-dispenser" /></template>
<style>
.bvu0653wk {
  d: path("M9.75 18.5a2.25 1.25 0 1 0 4.5 0a2.25 1.25 0 1 0-4.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vtfu0drzm {
  d: path("M8.75 4.75h6.5A1.75 1.75 0 0 1 17 6.5V8a1.75 1.75 0 0 1-1.75 1.75h-6.5A1.75 1.75 0 0 1 7 8V6.5a1.75 1.75 0 0 1 1.75-1.75m-.25 8h.01m3.49 0h.01m3.49 0h.01M6.5 15.5v5a1 1 0 0 0 1 1h9a1 1 0 0 0 1-1v-5");
}

.z0f71wboc {
  d: path("M8.375 2h7.25A4.375 4.375 0 0 1 20 6.375v4.75a4.375 4.375 0 0 1-4.375 4.375h-7.25A4.375 4.375 0 0 1 4 11.125v-4.75A4.375 4.375 0 0 1 8.375 2");
}

</style>
