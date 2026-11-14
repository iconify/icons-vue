<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clry7yc1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:heat-up" /></template>
<style>
.clry7yc1b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 16.5h7.5a2.25 2.25 0 0 1 2.25 2.25A2.25 2.25 0 0 1 12.25 21h-7.5a2.25 2.25 0 0 1-2.25-2.25a2.25 2.25 0 0 1 2.25-2.25m1.25-3q-1.5-2.5 0-5t0-5m5 10q-1.5-2.5 0-5t0-5M18.5 21V3.5m-3 3l3-3l3 3");
}

</style>
