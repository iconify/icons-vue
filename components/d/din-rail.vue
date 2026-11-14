<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m369rzbjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:din-rail" /></template>
<style>
.m369rzbjr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 5h.5a1.75 1.75 0 0 1 1.75 1.75v7.5A1.75 1.75 0 0 1 5.5 16H5a1.75 1.75 0 0 1-1.75-1.75v-7.5A1.75 1.75 0 0 1 5 5m6.75 0h.5A1.75 1.75 0 0 1 14 6.75v7.5A1.75 1.75 0 0 1 12.25 16h-.5A1.75 1.75 0 0 1 10 14.25v-7.5A1.75 1.75 0 0 1 11.75 5m6.75 0h.5a1.75 1.75 0 0 1 1.75 1.75v7.5A1.75 1.75 0 0 1 19 16h-.5a1.75 1.75 0 0 1-1.75-1.75v-7.5A1.75 1.75 0 0 1 18.5 5M4.25 16h15.5a1.75 1.75 0 0 1 1.75 1.75a1.75 1.75 0 0 1-1.75 1.75H4.25a1.75 1.75 0 0 1-1.75-1.75A1.75 1.75 0 0 1 4.25 16");
}

</style>
