<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yp0_tkb1w"/><path class="lqj2lxb1x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:humidity-gauge" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lqj2lxb1x {
  d: path("M12 12.75S9.75 15.5 9.75 17a2.25 2.25 0 0 0 4.5 0c0-1.5-2.25-4.25-2.25-4.25m0 0L15.75 9");
}

.yp0_tkb1w {
  d: path("M2.5 14.25a9.5 9.5 0 0 1 19 0");
}

</style>
