<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9nktgb7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:keyboard-wireless" /></template>
<style>
.u9nktgb7q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 11h13a3.5 3.5 0 0 1 3.5 3.5v3a3.5 3.5 0 0 1-3.5 3.5h-13A3.5 3.5 0 0 1 2 17.5v-3A3.5 3.5 0 0 1 5.5 11m.5 3.5h.01m3.99 0h.01m3.99 0h.01m3.99 0h.01M8.5 17.75h7M9.525 6.525a3.5 3.5 0 0 1 4.95 0M7.05 4.05a7 7 0 0 1 9.9 0");
}

</style>
