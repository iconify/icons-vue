<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c0jbwjwyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bass-drum" /></template>
<style>
.c0jbwjwyq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 10.5a8 8 0 1 0 16 0a8 8 0 1 0-16 0m4 7l-2 4m10-4l2 4m-14-11h2.5m13.5 0h-2.5M6.25 4.75L8 6.5m9.75-1.75L16 6.5");
}

</style>
