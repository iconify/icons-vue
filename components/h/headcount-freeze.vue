<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agh-b6rva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:headcount-freeze" /></template>
<style>
.agh-b6rva {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0M4 21c0-3.917 3.357-6.396 7.723-6.497m6.027-.753v8m-3.5-6l7 4m-7 0l7-4m-4.5-2l1 1l1-1m-2 8l1-1l1 1m2-6.75l-.25 1.25l1.25.25m0 2.5l-1.25.25l.25 1.25m-6-5.5l.25 1.25l-1.25.25m0 2.5l1.25.25l-.25 1.25");
}

</style>
