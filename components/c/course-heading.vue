<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mkhqlp6sj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:course-heading" /></template>
<style>
.mkhqlp6sj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12c2.5 1.5 3.5 4 3.5 6.5v3h-7v-3c0-2.5 1-5 3.5-6.5m0-2.75v-6.5M8.75 6L12 2.75L15.25 6");
}

</style>
