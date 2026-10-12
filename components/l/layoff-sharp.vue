<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p5b5tcm4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:layoff-sharp" /></template>
<style>
.p5b5tcm4t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 11.25V4.5H11v6.75M15.5 10V6.5m0 1c0-2 1.25-3.75 3.5-3.75c0 2-1.25 3.75-3.5 3.75ZM3.75 11.25h16.5L19 19.75l-.219 1.516l-1.531-.016H6.75l-1.531.016L5 19.75Zm6.25 3.5h4");
}

</style>
