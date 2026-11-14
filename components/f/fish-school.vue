<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ue36z7nbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fish-school" /></template>
<style>
.ue36z7nbw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13 5c-1.5-3-5.5-3-7 0L4 3v4l2-2c1.5 3 5.5 3 7 0m7.5 7c-1.5-3-5.5-3-7 0l-2-2v4l2-2c1.5 3 5.5 3 7 0m-8 7c-1.5-3-5.5-3-7 0l-2-2v4l2-2c1.5 3 5.5 3 7 0");
}

</style>
