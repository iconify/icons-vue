<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clzw3kbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bed-making" /></template>
<style>
.clzw3kbev {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4.5v15m0-9h16a2 2 0 0 1 2 2v7m-18-4h18m-13.25-9h1.5a2 2 0 0 1 2 2a2 2 0 0 1-2 2h-1.5a2 2 0 0 1-2-2a2 2 0 0 1 2-2m6.25 4l3 5");
}

</style>
