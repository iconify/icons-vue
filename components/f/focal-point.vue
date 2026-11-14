<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jnb526lpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:focal-point" /></template>
<style>
.jnb526lpr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 3.5q4 8.5 0 17q-4-8.5 0-17M2.5 7h5.25M2.5 12H7m-4.5 5h5.25m2.5-10L16 10m-5.75 7L16 14m4-2h.01");
}

</style>
