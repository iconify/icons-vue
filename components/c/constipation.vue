<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1n9labhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:constipation" /></template>
<style>
.m1n9labhz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 2.5h1.5A1.75 1.75 0 0 1 8 4.25v4.5a1.75 1.75 0 0 1-1.75 1.75h-1.5A1.75 1.75 0 0 1 3 8.75v-4.5A1.75 1.75 0 0 1 4.75 2.5m6.767 14.728a6 6 0 0 1-.517.022H9.25L10 21.5H4.75L5 16.75C3.75 15.5 3 13.5 3 11h13.5q0 .326-.022.639M10.5 11V9m3.75 9a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0M16 18h4");
}

</style>
