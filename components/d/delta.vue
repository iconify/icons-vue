<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yj4liac9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:delta" /></template>
<style>
.yj4liac9u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.525 6.212l6.008 10.68a1.75 1.75 0 0 1-1.525 2.608H5.992a1.75 1.75 0 0 1-1.525-2.608l6.008-10.68a1.75 1.75 0 0 1 3.05 0");
}

</style>
