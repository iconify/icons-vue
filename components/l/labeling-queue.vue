<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vh9wve0pj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:labeling-queue" /></template>
<style>
.vh9wve0pj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 4.75H21M10.5 12H21m-10.5 7.25H21M3.75 2.5h.576a1.5 1.5 0 0 1 1.122.503l.666.75a1.5 1.5 0 0 1 0 1.994l-.666.75A1.5 1.5 0 0 1 4.326 7H3.75A1.25 1.25 0 0 1 2.5 5.75v-2A1.25 1.25 0 0 1 3.75 2.5m0 7.25h.576a1.5 1.5 0 0 1 1.122.503l.666.75a1.5 1.5 0 0 1 0 1.994l-.666.75a1.5 1.5 0 0 1-1.122.503H3.75A1.25 1.25 0 0 1 2.5 13v-2a1.25 1.25 0 0 1 1.25-1.25m0 7.25h.576a1.5 1.5 0 0 1 1.122.503l.666.75a1.5 1.5 0 0 1 0 1.994l-.666.75a1.5 1.5 0 0 1-1.122.503H3.75a1.25 1.25 0 0 1-1.25-1.25v-2A1.25 1.25 0 0 1 3.75 17");
}

</style>
