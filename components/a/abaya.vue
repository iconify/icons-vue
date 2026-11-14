<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-vl5o_fo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:abaya" /></template>
<style>
.g-vl5o_fo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 3q2 1.5 4 0l4 1l3.5 7.5l-2.5 1.25L20 21H4l1-8.25l-2.5-1.25L6 4Zm2 .75V21");
}

</style>
