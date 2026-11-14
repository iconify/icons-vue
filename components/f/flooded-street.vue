<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jionf1gla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flooded-street" /></template>
<style>
.jionf1gla {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7 12.5l-4 9m14-9l4 9M2.5 4.5q2.25-1.5 4.75 0Q9.5 6 12 4.5q2.25-1.5 4.75 0Q19 6 21.5 4.5M2.5 9q2.25-1.5 4.75 0Q9.5 10.5 12 9q2.25-1.5 4.75 0Q19 10.5 21.5 9M12 13.5v2m0 3v3");
}

</style>
