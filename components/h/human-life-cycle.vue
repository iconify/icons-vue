<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpghtn5pf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:human-life-cycle" /></template>
<style>
.mpghtn5pf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.172 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c1.236 0 2.387.19 3.398.54M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0m9.5 9.5a2.9 2.9 0 0 1 5 0m0 0v-2.25m0 5.25a2.9 2.9 0 0 1-5 0m0 0v2.25");
}

</style>
