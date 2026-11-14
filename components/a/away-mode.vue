<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1x1fk3-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:away-mode" /></template>
<style>
.p1x1fk3-b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 19.25v-7.525a1.75 1.75 0 0 1 .513-1.238l2.75-2.75a1.75 1.75 0 0 1 2.474 0l2.75 2.75a1.75 1.75 0 0 1 .513 1.238v7.525A1.75 1.75 0 0 1 9.75 21h-5.5a1.75 1.75 0 0 1-1.75-1.75m14-14.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0M18 9.5L16.75 15m-2.25 6l2.25-6l2.5 3l-.5 3M15 12l2.5-1.75L20 12.5");
}

</style>
