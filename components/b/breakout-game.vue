<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rcqvg3dxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:breakout-game" /></template>
<style>
.rcqvg3dxi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 3h4.5A1.75 1.75 0 0 1 11 4.75A1.75 1.75 0 0 1 9.25 6.5h-4.5A1.75 1.75 0 0 1 3 4.75A1.75 1.75 0 0 1 4.75 3m10 0h4.5A1.75 1.75 0 0 1 21 4.75a1.75 1.75 0 0 1-1.75 1.75h-4.5A1.75 1.75 0 0 1 13 4.75A1.75 1.75 0 0 1 14.75 3m-5 6.25h4.5A1.75 1.75 0 0 1 16 11a1.75 1.75 0 0 1-1.75 1.75h-4.5A1.75 1.75 0 0 1 8 11a1.75 1.75 0 0 1 1.75-1.75M17.5 16a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M5 20.5h8");
}

</style>
