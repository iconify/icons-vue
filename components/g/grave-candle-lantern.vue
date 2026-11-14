<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dm3hui8kh"/><path class="zqdotubxu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:grave-candle-lantern" /></template>
<style>
.dm3hui8kh {
  d: path("m8.319 5.898l2.664-2.459a1.5 1.5 0 0 1 2.034 0l2.664 2.459A1.5 1.5 0 0 1 14.664 8.5H9.336a1.5 1.5 0 0 1-1.017-2.602M8.5 8.5h7A1.5 1.5 0 0 1 17 10v7a1.5 1.5 0 0 1-1.5 1.5h-7A1.5 1.5 0 0 1 7 17v-7a1.5 1.5 0 0 1 1.5-1.5m-2 10h11A1.5 1.5 0 0 1 19 20a1.5 1.5 0 0 1-1.5 1.5h-11A1.5 1.5 0 0 1 5 20a1.5 1.5 0 0 1 1.5-1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zqdotubxu {
  d: path("M12 11.25c2.25 2 2.5 4 0 4.5c-2.5-.5-2.25-2.5 0-4.5");
}

</style>
