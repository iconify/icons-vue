<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xxryylazw"/><path class="uwni876fg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:account-premium" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uwni876fg {
  d: path("M8.5 9L12 4l3.5 5m-7 0L12 19.5L15.5 9");
}

.xxryylazw {
  d: path("m4.358 7.302l1.854-2.317A2.63 2.63 0 0 1 8.262 4h7.476a2.63 2.63 0 0 1 2.05.985l1.854 2.317a2.625 2.625 0 0 1-.057 3.349l-5.592 6.524a2.625 2.625 0 0 1-3.986 0l-5.592-6.524a2.625 2.625 0 0 1-.057-3.349M3 9h18");
}

</style>
