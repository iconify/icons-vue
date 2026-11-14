<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="az4y26pcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hand-count-one" /></template>
<style>
.az4y26pcm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 13V4.75a1.75 1.75 0 0 1 3.5 0v5.75H17a2.5 2.5 0 0 1 2.5 2.5v2.5c0 3.5-2.75 6-6.5 6h-1c-4 0-7-2.5-7-6v-1A1.5 1.5 0 0 1 6.5 13Zm6.75-2.5v3");
}

</style>
