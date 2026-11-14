<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p49fdccjw"/><path class="ixq0prbxi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:coupon-wallet" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ixq0prbxi {
  d: path("M17.75 13.25h2A1.75 1.75 0 0 1 21.5 15v.5a1.75 1.75 0 0 1-1.75 1.75h-2A1.75 1.75 0 0 1 16 15.5V15a1.75 1.75 0 0 1 1.75-1.75m-15.25 2H16M6.75 6.5l4-.5");
}

.p49fdccjw {
  d: path("M5.125 10.5h13.75a2.625 2.625 0 0 1 2.625 2.625v5.75a2.625 2.625 0 0 1-2.625 2.625H5.125A2.625 2.625 0 0 1 2.5 18.875v-5.75A2.625 2.625 0 0 1 5.125 10.5m-1.375 0L3.5 8.75a1.75 1.75 0 0 0-.5-3.5L2.75 3.5l11-1.5l.25 1.75a1.75 1.75 0 0 0 .5 3.5l.25 3.25");
}

</style>
