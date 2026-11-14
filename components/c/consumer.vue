<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1735f32r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:consumer" /></template>
<style>
.n1735f32r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13.5V19a2 2 0 0 0 2 2h15a2 2 0 0 0 2-2v-5.5H16L14.5 16h-5L8 13.5Zm9.5-11V11M8.75 8L12 11.25L15.25 8");
}

</style>
