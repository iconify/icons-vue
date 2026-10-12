<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ac-ri8d0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:beach-umbrella" /></template>
<style>
.ac-ri8d0d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12a9 9 0 0 1 18 0q-2.25-1.5-4.5 0q-2.25-1.5-4.5 0q-2.25-1.5-4.5 0q-2.25-1.5-4.5 0m9 0v7.75m-8.5.75c2.83-1 5.67-1 8.5 0s5.67 1 8.5 0");
}

</style>
