<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ycv92cvuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:confetti-burst" /></template>
<style>
.ycv92cvuk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 8.75L5 5m10.25 3.75L19 5M8.75 15.25L5 19m10.25-3.75L19 19M12 3.5h.01m-.01 17h.01M3.5 12h.01m16.99 0h.01");
}

</style>
