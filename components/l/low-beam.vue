<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grm1-0l7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:low-beam" /></template>
<style>
.grm1-0l7k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 5.5c-3.9 0-7 2.9-7 6.5s3.1 6.5 7 6.5c1 0 1.75-.6 1.75-1.6V7.1c0-1-.75-1.6-1.75-1.6m5 1l6.5 2m-6.5 2l6.5 2m-6.5 2l6.5 2");
}

</style>
