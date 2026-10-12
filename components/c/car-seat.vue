<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="p_pa_tc-q"/><path class="rbbtc1bvq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:car-seat" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p_pa_tc-q {
  width: 5px;
  height: 3.25px;
  x: 4.25px;
  y: 4px;
  rx: 1.25px;
}

.rbbtc1bvq {
  d: path("M5.75 7.25H7q1.75 0 2.34 1.65l1.07 2.95q.59 1.65 2.34 1.65h4.75q1.75 0 1.75 1.75V16q0 1.75-1.75 1.75H9.25q-1.75 0-2.3-1.66l-2.4-7.18Q4 7.25 5.75 7.25m1.4 2.25l2 5.5m-5.4 6.25h16.5M10 17.75v3.5m6.5-3.5v3.5");
}

</style>
