<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="blq_18bfj"/><path class="h_n0_4bij"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cart-wheelchair" /></template>
<style>
.blq_18bfj {
  d: path("M2.5 2.5h2.25l2 9h8.5l2-6.5h-12M8 14.5h.01m5.49 0h.01m.99 4.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

.h_n0_4bij {
  d: path("M18 14v4.5h2.75l1 3M18 12.25h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
