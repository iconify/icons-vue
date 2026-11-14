<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1pbp2b1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:donate-coin-hand" /></template>
<style>
.i1pbp2b1d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 15h4C9 15 10 16 12 16h3a1.5 1.5 0 0 1 0 3h-4m4 0l4.5-2.75A1.75 1.75 0 0 1 21.25 19l-4.75 2.5h-14m7-14a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

</style>
