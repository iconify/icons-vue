<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3xb2xiuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hammock-tent" /></template>
<style>
.i3xb2xiuo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 2.5v19m17-19v19M7 10.5q5-1.5 10 0c0 5-2 7.5-5 7.5s-5-2.5-5-7.5m-3.5-4l3.5 4m13.5-4l-3.5 4");
}

</style>
