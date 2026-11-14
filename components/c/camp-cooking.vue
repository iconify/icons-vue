<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uamzpdbea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:camp-cooking" /></template>
<style>
.uamzpdbea {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4h18M5 4v6a3 3 0 0 0 3 3h8a3 3 0 0 0 3-3V4M7.5 20.75Q7 18 9 16.5q.5 1.75 1.5 2.25q.5-1.75 1.5-3q1 1.25 1.5 3q1-.5 1.5-2.25q2 1.5 1.5 4.25Z");
}

</style>
