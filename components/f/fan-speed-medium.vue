<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufe1a0wzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fan-speed-medium" /></template>
<style>
.ufe1a0wzp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 12a3.25 3.25 0 0 1 0-6a3.25 3.25 0 0 1 0 6a3.25 3.25 0 0 1 5.25 3a3.25 3.25 0 0 1-5.25-3a3.25 3.25 0 0 1-5.25 3a3.25 3.25 0 0 1 5.25-3m7.372-5.162a9 9 0 0 1 0 10.324m2.593-11.389a11.75 11.75 0 0 1 0 12.454");
}

</style>
