<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1m13o2cg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bank-head-office" /></template>
<style>
.d1m13o2cg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 8h6.5A1.75 1.75 0 0 1 17 9.75v10a1.75 1.75 0 0 1-1.75 1.75h-6.5A1.75 1.75 0 0 1 7 19.75v-10A1.75 1.75 0 0 1 8.75 8M12 2.5V8m0-5.5h4.5L15.25 4l1.25 1.5H12m-8 16h16M7 11h10M7 14h10M7 17h10m-6.75 0v4.5m3.5-4.5v4.5");
}

</style>
