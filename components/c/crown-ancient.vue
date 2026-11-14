<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="biv4y005x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crown-ancient" /></template>
<style>
.biv4y005x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 17.75v-6.714A1.464 1.464 0 0 1 5.5 10l.783.783a1.75 1.75 0 0 0 2.803-.455l1.349-2.698a1.75 1.75 0 0 1 3.13 0l1.349 2.698a1.75 1.75 0 0 0 2.803.455L18.5 10a1.464 1.464 0 0 1 2.5 1.036v6.714a1.75 1.75 0 0 1-1.75 1.75H4.75A1.75 1.75 0 0 1 3 17.75M3 16h18");
}

</style>
