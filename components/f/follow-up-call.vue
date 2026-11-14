<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tzj887bqn"/><path class="wg_8_-b4l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:follow-up-call" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tzj887bqn {
  d: path("M5 4h3l1.75 4.25l-2 1.5a10 10 0 0 0 6 6l1.5-2l4.25 1.75V18a2 2 0 0 1-2 2a15 15 0 0 1-15-13.5A2.5 2.5 0 0 1 5 4m15.5 7.5v-3A2.5 2.5 0 0 0 18 6h-5");
}

.wg_8_-b4l {
  d: path("m15 4l-2 2l2 2");
}

</style>
