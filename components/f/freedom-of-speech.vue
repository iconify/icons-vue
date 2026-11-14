<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g02rd-74d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:freedom-of-speech" /></template>
<style>
.g02rd-74d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 7H5a2.5 2.5 0 0 0-2.5 2.5v6A2.5 2.5 0 0 0 5 18h1v3.5l4-3.5h4.5a2.5 2.5 0 0 0 2.5-2.5V12m-8.5 2.5l12-12m-5.5 0h5.5V8");
}

</style>
