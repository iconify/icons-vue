<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xggy95uap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:artist-glove" /></template>
<style>
.xggy95uap {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 21v-4l-4.5-4.5A1.75 1.75 0 0 1 7 10l2 2V3.5h10.5V21Zm2.75-17.5v3m2.5-3v3m2.5-3v3M9 18.25h10.5");
}

</style>
