<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dut4e875o"/><path class="rh8200woq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:checkout-impulse-rack" /></template>
<style>
.dut4e875o {
  d: path("M6.625 2.5h10.75A2.625 2.625 0 0 1 20 5.125v9.75a2.625 2.625 0 0 1-2.625 2.625H6.625A2.625 2.625 0 0 1 4 14.875v-9.75A2.625 2.625 0 0 1 6.625 2.5m-.125 15v4m11-4v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rh8200woq {
  d: path("M9 5.5zA1.5 1.5 0 0 1 10.5 7v6A1.5 1.5 0 0 1 9 14.5A1.5 1.5 0 0 1 7.5 13V7A1.5 1.5 0 0 1 9 5.5m6 0zA1.5 1.5 0 0 1 16.5 7v6a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5V7A1.5 1.5 0 0 1 15 5.5");
}

</style>
