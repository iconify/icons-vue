<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-k5k4bcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:darbuka" /></template>
<style>
.r-k5k4bcx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 3.5h15c0 5.5-5.5 6.5-6 9.5l1.5 7.5H9l1.5-7.5c-.5-3-6-4-6-9.5m6 9.5h3");
}

</style>
