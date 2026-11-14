<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kh7_kibkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:audio-falloff" /></template>
<style>
.kh7_kibkt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.723 17.75L7 13.5H3v-6h4L12 3v14.573M15 7.5q1.391 2.087.847 4.174m-.652 1.518q-.092.154-.195.308M17.75 5q2.122 3.335 1.671 6.67M18 14.5v7m-3-3l3 3l3-3");
}

</style>
