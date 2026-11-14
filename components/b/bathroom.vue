<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="my7zrkbjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bathroom" /></template>
<style>
.my7zrkbjd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 2.5h7A1.5 1.5 0 0 1 17 4v4a1.5 1.5 0 0 1-1.5 1.5h-7A1.5 1.5 0 0 1 7 8V4a1.5 1.5 0 0 1 1.5-1.5M3.5 15h17v1c0 3.5-4 5.5-8.5 5.5s-8.5-2-8.5-5.5Zm12 0v-2.25c0-1.25-2.5-1.25-3 0");
}

</style>
