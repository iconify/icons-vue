<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="asfhay5lm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:amphibious-vehicle" /></template>
<style>
.asfhay5lm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14.5v-4l3.5-1L8.5 5h6l3 4.5l4 1v4h-3a2.25 2.25 0 0 0-4.5 0h-4a2.25 2.25 0 0 0-4.5 0Zm.5 4.25q2.25-1.5 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
