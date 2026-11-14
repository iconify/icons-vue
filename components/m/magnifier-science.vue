<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkutolbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:magnifier-science" /></template>
<style>
.kkutolbbn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 8.5a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0m1.5 4l-4 4m12 1a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
