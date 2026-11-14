<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dqms21ipr"/><path class="lyiaeuhaq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:heart-candle" /></template>
<style>
.dqms21ipr {
  d: path("M8.625 9h6.75A2.625 2.625 0 0 1 18 11.625v7.25a2.625 2.625 0 0 1-2.625 2.625h-6.75A2.625 2.625 0 0 1 6 18.875v-7.25A2.625 2.625 0 0 1 8.625 9M12 2.5c2.25 2 2.25 3.75 0 3.75S9.75 4.5 12 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lyiaeuhaq {
  d: path("m12 18l-2.5-2.5a1.75 1.75 0 0 1 2.5-2.25a1.75 1.75 0 0 1 2.5 2.25Z");
}

</style>
