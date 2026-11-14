<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pffqf3bly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lawn-edger" /></template>
<style>
.pffqf3bly {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 14.75a4 4 0 1 0 8 0a4 4 0 1 0-8 0m4 0h.01M10.25 12l8.25-8.25M17 2.5l3.25 3.25M2.5 21.5h19m-6.5 0v-3m3 3V18");
}

</style>
