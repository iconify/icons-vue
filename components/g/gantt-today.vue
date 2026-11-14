<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z111f0f7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gantt-today" /></template>
<style>
.z111f0f7s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 5h5A1.5 1.5 0 0 1 11 6.5A1.5 1.5 0 0 1 9.5 8h-5A1.5 1.5 0 0 1 3 6.5A1.5 1.5 0 0 1 4.5 5M8 10.75h5a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5H8a1.5 1.5 0 0 1-1.5-1.5a1.5 1.5 0 0 1 1.5-1.5m3.5 5.75h8A1.5 1.5 0 0 1 21 18a1.5 1.5 0 0 1-1.5 1.5h-8A1.5 1.5 0 0 1 10 18a1.5 1.5 0 0 1 1.5-1.5m6-10.75V21.5m0-18.5h.01");
}

</style>
