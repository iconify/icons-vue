<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1nbrbwlw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:edit-lock" /></template>
<style>
.y1nbrbwlw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.303 4.99l.707.707a1.5 1.5 0 0 1 0 2.121l-5.689 5.689a1.5 1.5 0 0 1-.766.41l-1.323.265a1.202 1.202 0 0 1-1.414-1.414l.265-1.323a1.5 1.5 0 0 1 .41-.766l5.689-5.689a1.5 1.5 0 0 1 2.121 0M17.25 16h2.5a1.75 1.75 0 0 1 1.75 1.75v1a1.75 1.75 0 0 1-1.75 1.75h-2.5a1.75 1.75 0 0 1-1.75-1.75v-1A1.75 1.75 0 0 1 17.25 16m-.5 0v-1.25a1.75 1.75 0 0 1 3.5 0V16");
}

</style>
