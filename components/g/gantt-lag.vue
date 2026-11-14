<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nth5ffbmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gantt-lag" /></template>
<style>
.nth5ffbmb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 3H8a2 2 0 0 1 2 2a2 2 0 0 1-2 2H4.5a2 2 0 0 1-2-2a2 2 0 0 1 2-2M16 17h3.5a2 2 0 0 1 2 2a2 2 0 0 1-2 2H16a2 2 0 0 1-2-2a2 2 0 0 1 2-2m-8.5-5h9M9.75 9.75L7.5 12l2.25 2.25m4.5-4.5L16.5 12l-2.25 2.25");
}

</style>
