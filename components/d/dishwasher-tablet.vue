<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_prnjtwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dishwasher-tablet" /></template>
<style>
.u_prnjtwt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 9h8a3.5 3.5 0 0 1 3.5 3.5v4A3.5 3.5 0 0 1 14 20H6a3.5 3.5 0 0 1-3.5-3.5v-4A3.5 3.5 0 0 1 6 9m4 0v11m9.5-16.5Q19.5 6 22 6q-2.5 0-2.5 2.5Q19.5 6 17 6q2.5 0 2.5-2.5");
}

</style>
