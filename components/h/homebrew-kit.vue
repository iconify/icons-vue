<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojv2rwb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:homebrew-kit" /></template>
<style>
.ojv2rwb6a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 8h13.5a1.25 1.25 0 0 1 1.25 1.25a1.25 1.25 0 0 1-1.25 1.25H3.75A1.25 1.25 0 0 1 2.5 9.25A1.25 1.25 0 0 1 3.75 8m9.666 13.5H7.75q-2 0-2.25-2l-2-9h14l-.033.298M10.5 8V5.5m0-3zA1.5 1.5 0 0 1 12 4a1.5 1.5 0 0 1-1.5 1.5A1.5 1.5 0 0 1 9 4a1.5 1.5 0 0 1 1.5-1.5m7.5 11h2v1.75q1.75.75 1.75 2.75v3.75h-5.5V18q0-2 1.75-2.75Z");
}

</style>
