<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7z4qy0tm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bird-feeder-garden" /></template>
<style>
.x7z4qy0tm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 10L12 5.5l7.5 4.5M7 8.5v7m10-7v7m-12 0h14l-1.5 4h-11Zm7-13v3m6.25 12h3.25m-12.25-2q2.75-2.75 5.5 0");
}

</style>
