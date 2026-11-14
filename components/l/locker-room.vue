<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdaslocdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:locker-room" /></template>
<style>
.gdaslocdg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 3h3.5a1.75 1.75 0 0 1 1.75 1.75v14.5A1.75 1.75 0 0 1 8.75 21h-3.5a1.75 1.75 0 0 1-1.75-1.75V4.75A1.75 1.75 0 0 1 5.25 3m10 0h3.5a1.75 1.75 0 0 1 1.75 1.75v14.5A1.75 1.75 0 0 1 18.75 21h-3.5a1.75 1.75 0 0 1-1.75-1.75V4.75A1.75 1.75 0 0 1 15.25 3M9 10.5V12m6-1.5V12M5.75 6.5h2.5m7.5 0h2.5");
}

</style>
