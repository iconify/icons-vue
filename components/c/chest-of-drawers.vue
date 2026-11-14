<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8w-00bho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chest-of-drawers" /></template>
<style>
.m8w-00bho {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 19.5V5q0-2 2-2h14q2 0 2 2v14.5Zm2 0v2m14-2v2M3 8.5h18M3 14h18M10 5.75h4m-4 5.5h4m-4 5.5h4");
}

</style>
