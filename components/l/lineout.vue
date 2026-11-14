<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3q2sdvaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lineout" /></template>
<style>
.j3q2sdvaq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 4.75a3.5 2.25 0 1 0 7 0a3.5 2.25 0 1 0-7 0M2.75 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-.25 9.5v-2A2.5 2.5 0 0 1 5 17h3.5l1.75-7.25m7 2.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0m4.25 9.5v-2A2.5 2.5 0 0 0 19 17h-3.5l-1.75-7.25");
}

</style>
