<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7qksfb8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:blocking-marks" /></template>
<style>
.j7qksfb8c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.793 5.5h11.338a1.75 1.75 0 0 1 1.672 2.265l-2.923 9.5a1.75 1.75 0 0 1-1.673 1.235H4.869a1.75 1.75 0 0 1-1.672-2.265l2.923-9.5A1.75 1.75 0 0 1 7.793 5.5M8.5 9.25h8m-4 0L11.25 15");
}

</style>
