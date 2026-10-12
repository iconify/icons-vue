<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="azzxabcek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bike-lane" /></template>
<style>
.azzxabcek {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75v18.5m18.5-18.5v18.5m-10.5-12a2.5 2.5 0 1 1-5 0a2.5 2.5 0 1 1 5 0m7.5 0a2.5 2.5 0 1 1-5 0a2.5 2.5 0 1 1 5 0m-10 0L11.5 5l4.25 4.25M10.25 5h2.5M12 21v-6m-2.25 2.25L12 15l2.25 2.25");
}

</style>
