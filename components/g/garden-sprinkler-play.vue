<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxu_kbnve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:garden-sprinkler-play" /></template>
<style>
.bxu_kbnve {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 14.5a3.5 3.5 0 0 1 7 0Zm3.5 0v7m0-13.25V2.5M8.5 9c-1.5-3-4-4-6-2m13 2c1.5-3 4-4 6-2");
}

</style>
