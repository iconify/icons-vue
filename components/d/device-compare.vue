<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvltygt5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:device-compare" /></template>
<style>
.cvltygt5m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 6h1a3.5 3.5 0 0 1 3.5 3.5v6A3.5 3.5 0 0 1 7 19H6a3.5 3.5 0 0 1-3.5-3.5v-6A3.5 3.5 0 0 1 6 6m11 0h1a3.5 3.5 0 0 1 3.5 3.5v6A3.5 3.5 0 0 1 18 19h-1a3.5 3.5 0 0 1-3.5-3.5v-6A3.5 3.5 0 0 1 17 6M6.5 16v.5m11-.5v.5M12 2.5v1");
}

</style>
