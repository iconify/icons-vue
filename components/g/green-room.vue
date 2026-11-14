<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6_cwdbbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:green-room" /></template>
<style>
.y6_cwdbbd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 3h5A3.5 3.5 0 0 1 18 6.5v7a3.5 3.5 0 0 1-3.5 3.5h-5A3.5 3.5 0 0 1 6 13.5v-7A3.5 3.5 0 0 1 9.5 3M12 17v3.5m-3.5 0h7M2.5 7A1.75 1.75 0 0 1 6 7a1.75 1.75 0 0 1-3.5 0m0 6A1.75 1.75 0 0 1 6 13a1.75 1.75 0 0 1-3.5 0M18 7a1.75 1.75 0 0 1 3.5 0A1.75 1.75 0 0 1 18 7m0 6a1.75 1.75 0 0 1 3.5 0a1.75 1.75 0 0 1-3.5 0");
}

</style>
