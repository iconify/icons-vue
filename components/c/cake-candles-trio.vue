<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zxgd-bbvt"/><path class="z0-dt6dnn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cake-candles-trio" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z0-dt6dnn {
  d: path("M3.5 16q2.25 2 4.5 0q2-2 4 0t4 0q2.25-2 4.5 0m-14-7v3M12 9v3m5.5-3v3m-11-9.5c1.25 1.5 1.25 3.75 0 3.75S5.25 4 6.5 2.5m5.5 0c1.25 1.5 1.25 3.75 0 3.75S10.75 4 12 2.5m5.5 0c1.25 1.5 1.25 3.75 0 3.75S16.25 4 17.5 2.5");
}

.zxgd-bbvt {
  d: path("M7 12h10a3.5 3.5 0 0 1 3.5 3.5v2A3.5 3.5 0 0 1 17 21H7a3.5 3.5 0 0 1-3.5-3.5v-2A3.5 3.5 0 0 1 7 12");
}

</style>
