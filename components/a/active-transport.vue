<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fz0urq78y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:active-transport" /></template>
<style>
.fz0urq78y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 10h3A1.75 1.75 0 0 1 9 11.75v.5A1.75 1.75 0 0 1 7.25 14h-3a1.75 1.75 0 0 1-1.75-1.75v-.5A1.75 1.75 0 0 1 4.25 10m12.5 0h3a1.75 1.75 0 0 1 1.75 1.75v.5A1.75 1.75 0 0 1 19.75 14h-3A1.75 1.75 0 0 1 15 12.25v-.5A1.75 1.75 0 0 1 16.75 10M12 21.5V3M8 7l4-4l4 4");
}

</style>
