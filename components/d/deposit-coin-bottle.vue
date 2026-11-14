<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mxo20341x"/><path class="ndzwabc2p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:deposit-coin-bottle" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mxo20341x {
  d: path("M10.25 9.75V12c0 1-2.25 1.5-2.25 3.5V20a1.5 1.5 0 0 0 1.5 1.5h5A1.5 1.5 0 0 0 16 20v-4.5c0-2-2.25-2.5-2.25-3.5V9.75m-4.5-5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

.ndzwabc2p {
  d: path("M11.5 2.5H13A2.25 2.25 0 0 1 13 7h-1.5");
}

</style>
