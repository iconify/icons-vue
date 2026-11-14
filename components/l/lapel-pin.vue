<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7vffxluf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lapel-pin" /></template>
<style>
.m7vffxluf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 8a4 4 0 1 0 8 0a4 4 0 1 0-8 0m1.25 2.75L4 20m3.5-5.268L9.268 16.5a1.25 1.25 0 0 1 0 1.768a1.25 1.25 0 0 1-1.768 0L5.732 16.5a1.25 1.25 0 0 1 0-1.768a1.25 1.25 0 0 1 1.768 0");
}

</style>
