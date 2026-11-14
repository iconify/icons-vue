<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="znhevz6kr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cinema-camera" /></template>
<style>
.znhevz6kr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 9h5.5a3.5 3.5 0 0 1 3.5 3.5v3a3.5 3.5 0 0 1-3.5 3.5H6a3.5 3.5 0 0 1-3.5-3.5v-3A3.5 3.5 0 0 1 6 9m10.122 2.069l3-1.154a1.75 1.75 0 0 1 2.378 1.633v4.404a1.75 1.75 0 0 1-2.378 1.633l-3-1.154A1.75 1.75 0 0 1 15 14.798v-2.096a1.75 1.75 0 0 1 1.122-1.633M5 9V6h7.5v3");
}

</style>
