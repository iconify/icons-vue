<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxxlzmvuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:genre-noir" /></template>
<style>
.wxxlzmvuc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.5 14.5l1-7Q9.75 5 12 7q2.25-2 4.5.5l1 7m-15 0q1.5 3 9.5 3t9.5-3M7 11.5h10");
}

</style>
