<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="el3fspbqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:door-sensor" /></template>
<style>
.el3fspbqe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 4h1a3.5 3.5 0 0 1 3.5 3.5v9A3.5 3.5 0 0 1 7 20H6a3.5 3.5 0 0 1-3.5-3.5v-9A3.5 3.5 0 0 1 6 4m7.5 3h3a5 5 0 0 1 0 10h-3v-3h3a2 2 0 0 0 0-4h-3Zm-7 1h.01");
}

</style>
