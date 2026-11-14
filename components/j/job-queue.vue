<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xl6039j-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:job-queue" /></template>
<style>
.xl6039j-f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 3.5H21V7H10.5Zm0 6.75H21v3.5H10.5Zm0 6.75H21v3.5H10.5ZM3 5.25h4.5M5.25 3L7.5 5.25L5.25 7.5");
}

</style>
