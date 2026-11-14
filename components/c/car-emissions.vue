<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vh31u_b2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:car-emissions" /></template>
<style>
.vh31u_b2q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 20v-4l3-.75L10.5 12h6l2.5 3.25l2.5.75v4h-1.75a2 2 0 0 0-4 0H11.5a2 2 0 0 0-4 0ZM4.5 9a2 2 0 0 1 0-4a2.5 2.5 0 0 1 5 0a2 2 0 0 1 0 4Z");
}

</style>
