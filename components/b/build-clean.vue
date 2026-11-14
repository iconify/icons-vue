<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t2kv-0buk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:build-clean" /></template>
<style>
.t2kv-0buk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 5.5q1 6.5 7.5 7.5q-6.5 1-7.5 7.5Q9 14 2.5 13Q9 12 10 5.5M18.5 3q.35 2.15 2.5 2.5q-2.15.35-2.5 2.5q-.35-2.15-2.5-2.5q2.15-.35 2.5-2.5");
}

</style>
