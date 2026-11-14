<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lt-mps59m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:build-failed" /></template>
<style>
.lt-mps59m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.208 21.39L12 21.5L3.5 17V7L12 2.5L20.5 7v5.382M3.5 7l8.5 4.5M20.5 7L12 11.5m0 0v10m3-6.5l6.5 6.5m0-6.5L15 21.5");
}

</style>
