<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zaf_e95mu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:artist-hand-model" /></template>
<style>
.zaf_e95mu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 10h3a3 3 0 0 1 3 3a3 3 0 0 1-3 3h-3a3 3 0 0 1-3-3a3 3 0 0 1 3-3m-1.25 0V4m2.75 6V2.5m2.75 7.5V4M9 13L6 9.5m7.5 6.5v5.5m-4 0h8");
}

</style>
