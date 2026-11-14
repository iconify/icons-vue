<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzbwlxbyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fabric-stretch" /></template>
<style>
.fzbwlxbyn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 7q2.5-1.5 5 0t5 0v10q-2.5-1.5-5 0t-5 0Zm-4.5 5h19M4.25 10.25L2.5 12l1.75 1.75m15.5-3.5L21.5 12l-1.75 1.75");
}

</style>
