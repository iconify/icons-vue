<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="me2tepbmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:home-cinema" /></template>
<style>
.me2tepbmw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.759 9h10.482a1.5 1.5 0 0 1 1.481 1.737l-1.52 9.5a1.5 1.5 0 0 1-1.481 1.263H8.279a1.5 1.5 0 0 1-1.481-1.263l-1.52-9.5A1.5 1.5 0 0 1 6.759 9M5 9c-.5-2.5 2-4 3.5-2.75c.5-2.5 4-3.25 5.25-1c1.5-1.5 4.5-.75 4.25 1.75c1.5.25 1.5 1.75 1 2M9.75 9l.5 12.5m4-12.5l-.5 12.5");
}

</style>
