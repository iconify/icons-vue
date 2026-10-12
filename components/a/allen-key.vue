<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fg5liwgya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:allen-key" /></template>
<style>
.fg5liwgya {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 2.75h2.5Q9.5 2.75 9.5 4v11.25q0 1.25 1.25 1.25H20q1.25 0 1.25 1.25V20q0 1.25-1.25 1.25H5.75Q4.5 21.25 4.5 20V4q0-1.25 1.25-1.25M7 5.25v9");
}

</style>
