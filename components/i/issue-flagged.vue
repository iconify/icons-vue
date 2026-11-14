<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-digv10q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:issue-flagged" /></template>
<style>
.q-digv10q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 19a8 8 0 1 1 8-8m-8 0h.01m4.49 3.75v6.5M17 15h2.675a.553.553 0 0 1 .45.875l-.002.003a1.5 1.5 0 0 0 0 1.744l.002.003a.553.553 0 0 1-.45.875H17a1.5 1.5 0 0 1-1.5-1.5v-.5A1.5 1.5 0 0 1 17 15");
}

</style>
