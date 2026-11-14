<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrjjvsb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baby-blanket" /></template>
<style>
.wrjjvsb3z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 5q2.25-2 4.5 0T12 5t4.5 0T21 5v14a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Zm10 16l8-8");
}

</style>
