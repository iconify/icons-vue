<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2gwo962m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:loading-circle" /></template>
<style>
.y2gwo962m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 3.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0M17 6a1 1 0 1 0 2 0a1 1 0 1 0-2 0m2.5 6a1 1 0 1 0 2 0a1 1 0 1 0-2 0M17 18a1 1 0 1 0 2 0a1 1 0 1 0-2 0m-6 2.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0M5 18a1 1 0 1 0 2 0a1 1 0 1 0-2 0m-2.5-6a1 1 0 1 0 2 0a1 1 0 1 0-2 0M5 6a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

</style>
