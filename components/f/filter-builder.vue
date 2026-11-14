<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3ba31b6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:filter-builder" /></template>
<style>
.g3ba31b6n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 3h8a2.25 2.25 0 0 1 2.25 2.25a2.25 2.25 0 0 1-2.25 2.25h-8A2.25 2.25 0 0 1 9 5.25A2.25 2.25 0 0 1 11.25 3m0 6.75h8A2.25 2.25 0 0 1 21.5 12a2.25 2.25 0 0 1-2.25 2.25h-8A2.25 2.25 0 0 1 9 12a2.25 2.25 0 0 1 2.25-2.25m0 6.75h8a2.25 2.25 0 0 1 2.25 2.25A2.25 2.25 0 0 1 19.25 21h-8A2.25 2.25 0 0 1 9 18.75a2.25 2.25 0 0 1 2.25-2.25M7 5.25H3.5v13.5H7M3.5 12H7m7-9v4.5m0 2.25v4.5m0 2.25V21");
}

</style>
