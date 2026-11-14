<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vutc0yjaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lab-respirator" /></template>
<style>
.vutc0yjaq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 8.5q6.5-2.5 13 0V15q-6.5 4-13 0Zm0 .5C2 9 2 15 5.5 15m13-6c3.5 0 3.5 6 0 6M9 10.75h6M9 13.5h6");
}

</style>
