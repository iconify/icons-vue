<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mfespgbkt"/><path class="x2tbj_frr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hair-loss-treatment" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mfespgbkt {
  d: path("M7.25 21.5V18c-2.25-1.5-3-3.5-3-5.75c0-3.75 2.75-6.5 6.5-6.5C14 5.75 16.5 8 16.5 11.5l1.5 3q0 .75-.75.75h-.75v2c0 1-.75 1.75-1.5 1.75h-1.75v2.5");
}

.x2tbj_frr {
  d: path("M8 6.5q-.375-1.875.75-3M11 5.75c0-1.25.5-2.25 1.25-2.75M17 3c1 .5 1.25 1.5 2 2m.75 2.5c.75.5 1 1.5 1.75 1.75m-6.75 1.5h.01");
}

</style>
