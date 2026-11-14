<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bfst0dy0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:biome" /></template>
<style>
.bfst0dy0b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.25c3.5-5 9.5-6 19-1M9 16v-3.25m-2.75 0a2.5 2.5 0 0 1-.75-4.5a3.5 3.5 0 0 1 7 0a2.5 2.5 0 0 1-.75 4.5ZM16 6.25a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
