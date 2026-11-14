<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqc_a1b3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:beluga" /></template>
<style>
.qqc_a1b3r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 14c0-4 2.5-6 6-6c5 0 7.5 4 9.5 6.5l2.5-2V18l-2.5-1.5q-3.75 3-9 3c-4 0-6.5-2-6.5-5.5m4-1h.01M5.75 5.25L4.5 3m3.75 2.25L9.5 3");
}

</style>
