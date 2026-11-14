<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fabpzceyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:camera-floodlight" /></template>
<style>
.fabpzceyu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 3.5h11.5a2.75 2.75 0 0 1 2.75 2.75A2.75 2.75 0 0 1 17.75 9H6.25A2.75 2.75 0 0 1 3.5 6.25A2.75 2.75 0 0 1 6.25 3.5M8 16.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0M6.5 12L5 15.5M17.5 12l1.5 3.5m-7 1h.01");
}

</style>
