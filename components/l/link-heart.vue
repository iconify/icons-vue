<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-8ugdb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:link-heart" /></template>
<style>
.w-8ugdb0c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 7.5H7.5a4.5 4.5 0 0 0 0 9H9m6-9h1.5A4.5 4.5 0 0 1 21 12M8.5 12h7m2.5 9s-3-1.75-3-4c0-1 .75-1.75 1.5-1.75q1.125 0 1.5.75q.375-.75 1.5-.75c.75 0 1.5.75 1.5 1.75c0 2.25-3 4-3 4");
}

</style>
