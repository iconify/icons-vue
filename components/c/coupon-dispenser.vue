<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lvt2mix-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:coupon-dispenser" /></template>
<style>
.lvt2mix-v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 2.5h16A1.5 1.5 0 0 1 21.5 4A1.5 1.5 0 0 1 20 5.5H4A1.5 1.5 0 0 1 2.5 4A1.5 1.5 0 0 1 4 2.5m3.625 3h8.75A2.625 2.625 0 0 1 19 8.125v2.75a2.625 2.625 0 0 1-2.625 2.625h-8.75A2.625 2.625 0 0 1 5 10.875v-2.75A2.625 2.625 0 0 1 7.625 5.5m.375 8v8h8v-8m-5.75 6.25l3.5-4M10.5 16h.01m2.99 3.5h.01m1.99-10h.01");
}

</style>
