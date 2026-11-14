<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uz3uh5lqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hormone-signal" /></template>
<style>
.uz3uh5lqp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 3s-6 7-6 11a6 6 0 0 0 12 0c0-4-6-11-6-11m7.794 6.5a9 9 0 0 1 0 9M18.83 7.117a12 12 0 0 1 0 13.766");
}

</style>
