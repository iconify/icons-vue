<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwd5zb3kd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drive-shaft" /></template>
<style>
.cwd5zb3kd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 8za1 1 0 0 1 1 1v6a1 1 0 0 1-1 1a1 1 0 0 1-1-1V9a1 1 0 0 1 1-1m1 1.5h2a2.5 2.5 0 0 1 0 5h-2M9 12h6m4.5-2.5h-2a2.5 2.5 0 0 0 0 5h2m1-6.5za1 1 0 0 1 1 1v6a1 1 0 0 1-1 1a1 1 0 0 1-1-1V9a1 1 0 0 1 1-1");
}

</style>
