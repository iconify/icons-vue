<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6abvlbkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fish-oil" /></template>
<style>
.y6abvlbkn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 7.25c3-4.5 9.5-4.5 12.5 0l5-3.5v7l-5-3.5c-3 4.5-9.5 4.5-12.5 0M6 17.5a6 3.5 0 1 0 12 0a6 3.5 0 1 0-12 0M7.5 6.75h.01");
}

</style>
