<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jx3v1z6mi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hat-stand" /></template>
<style>
.jx3v1z6mi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8 8l.5-3.75c1-1.75 6-1.75 7 0L16 8M3 8h18c-1.5 2-16.5 2-18 0m9 1.5V19m-4.5 2.5L12 19l4.5 2.5M8 6.25h8");
}

</style>
