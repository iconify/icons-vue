<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agb4-b_qk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:construction-progress" /></template>
<style>
.agb4-b_qk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 15.5h13a3 3 0 0 1 3 3a3 3 0 0 1-3 3h-13a3 3 0 0 1-3-3a3 3 0 0 1 3-3m0-8h2A1.5 1.5 0 0 1 9 9v2a1.5 1.5 0 0 1-1.5 1.5h-2A1.5 1.5 0 0 1 4 11V9a1.5 1.5 0 0 1 1.5-1.5m5 0h2A1.5 1.5 0 0 1 14 9v2a1.5 1.5 0 0 1-1.5 1.5h-2A1.5 1.5 0 0 1 9 11V9a1.5 1.5 0 0 1 1.5-1.5M8 2.5h2A1.5 1.5 0 0 1 11.5 4v2A1.5 1.5 0 0 1 10 7.5H8A1.5 1.5 0 0 1 6.5 6V4A1.5 1.5 0 0 1 8 2.5m-2.5 16h9");
}

</style>
