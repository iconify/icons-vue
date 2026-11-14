<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7a0d6_7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cider" /></template>
<style>
.w7a0d6_7k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.5 13.489V12.5q0-3-4-4.5V5h-3v3q-4 1.5-4 4.5V20q0 1.5 1.5 1.5h7.432M8.25 2.5h1.5A1.25 1.25 0 0 1 11 3.75A1.25 1.25 0 0 1 9.75 5h-1.5A1.25 1.25 0 0 1 7 3.75A1.25 1.25 0 0 1 8.25 2.5M18 16.25c-1.25-1-3.5-.5-3.5 2.25c0 2.25 1.75 3.5 3.5 2.75c1.75.75 3.5-.5 3.5-2.75c0-2.75-2.25-3.25-3.5-2.25m0 0l.75-2");
}

</style>
