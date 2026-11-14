<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p41vfebhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ampoule-break" /></template>
<style>
.p41vfebhh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 6.5v2c0 1.25-2.5 2-2.5 4.5v5.5a2 2 0 0 0 2 2h4a2 2 0 0 0 2-2V13c0-2.5-2.5-3.25-2.5-4.5v-2l-1.5 1Zm8.135 1.191l2.376-2.218a1.5 1.5 0 0 1 .549-.326l1.19-.397a.791.791 0 0 1 1 1l-.397 1.19a1.5 1.5 0 0 1-.326.549l-2.218 2.376a1.5 1.5 0 0 1-2.157.037l-.054-.054a1.5 1.5 0 0 1 .037-2.157");
}

</style>
