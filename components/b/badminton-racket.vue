<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7x_2crvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:badminton-racket" /></template>
<style>
.d7x_2crvx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 9a6 4.5 0 1 0 12 0A6 4.5 0 1 0 9 9m1.75 4.25l-2.5 2.5m-.129.129za1.5 1.5 0 0 1 0 2.121L6 20.121a1.5 1.5 0 0 1-2.121 0a1.5 1.5 0 0 1 0-2.121L6 15.879a1.5 1.5 0 0 1 2.121 0m2.636-2.636l8.486-8.486m-7.425 1.061l6.364 6.364");
}

</style>
