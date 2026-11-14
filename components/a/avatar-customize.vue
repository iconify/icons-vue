<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-qvxb72q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:avatar-customize" /></template>
<style>
.x-qvxb72q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.972 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c1.478 0 2.835.272 3.976.764M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0m8.25 12.875v-.754a1.5 1.5 0 0 1 .439-1.06l2.5-2.5a1.5 1.5 0 0 1 2.122 0l.628.628a1.5 1.5 0 0 1 0 2.122l-2.5 2.5a1.5 1.5 0 0 1-1.06.439h-.754a1.375 1.375 0 0 1-1.375-1.375");
}

</style>
