<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lrigp0bmq"/><path class="qv75-lwvt"/><path class="dc6k549zu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:coupon-stack" /></template>
<style>
.dc6k549zu {
  d: path("M8.5 6h13v7.5M6 16.75h4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lrigp0bmq {
  d: path("M2.5 12h13v3a1.5 1.5 0 0 0 0 3v3.5h-13V18a1.5 1.5 0 0 0 0-3Z");
}

.qv75-lwvt {
  d: path("M5.5 9h13v7.5");
}

</style>
