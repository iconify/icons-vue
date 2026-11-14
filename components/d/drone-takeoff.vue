<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6z9p2q8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drone-takeoff" /></template>
<style>
.o6z9p2q8h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5h6m-3 0V8H9m2.5-2.25h1a2.5 2.5 0 0 1 2.5 2.5a2.5 2.5 0 0 1-2.5 2.5h-1A2.5 2.5 0 0 1 9 8.25a2.5 2.5 0 0 1 2.5-2.5m4-2.25h6m-3 0V8H15m-4.5 2.75L9 13.5m4.5-2.75L15 13.5m3 7.5v-6m-2.5 2.5L18 15l2.5 2.5");
}

</style>
