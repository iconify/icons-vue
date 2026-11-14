<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8rmr-n0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:canvas-pan" /></template>
<style>
.e8rmr-n0a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 7v8.5c0 3.5 2.5 6 6 6c2.5 0 4-1 5.25-3L19 13.75M8 11V4m3 7V3m3 13.5v-11");
}

</style>
