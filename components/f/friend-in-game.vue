<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0zckx_ve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:friend-in-game" /></template>
<style>
.v0zckx_ve {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 8a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0M2.5 20.5c0-4 3-6.25 6.5-6.25c1.246 0 2.428.285 3.434.833M14 5.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m.25 6.25c2.17 0 4.015.522 5.3 1.465M16.5 16H20c1.25 0 2 1 2 2.5V20c0 1-1 1.5-1.75 1L19 20h-1.5l-1.25 1c-.75.5-1.75 0-1.75-1v-1.5c0-1.5.75-2.5 2-2.5");
}

</style>
