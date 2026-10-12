<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sk2s3cbet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bowl" /></template>
<style>
.sk2s3cbet {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 9.75h18.5c0 4.75-3.75 8.5-8.25 8.5h-2c-4.5 0-8.25-3.75-8.25-8.5m2 3.25h14.5M9 18.25l-.5 3h7l-.5-3");
}

</style>
