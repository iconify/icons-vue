<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvcfpmbby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:census" /></template>
<style>
.xvcfpmbby {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 7a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0m-3 14.5v-1c0-3 2.75-5.75 6.25-5.75s6.25 2.75 6.25 5.75v1M2.5 10.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0m15 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-15 7.75c0-1.75.75-2.75 2-3m17 3c0-1.75-.75-2.75-2-3");
}

</style>
