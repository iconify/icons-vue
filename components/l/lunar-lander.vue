<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="roix5jzfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lunar-lander" /></template>
<style>
.roix5jzfa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 3.5h6l2.5 3v5h-11v-5Zm-1.5 8l-3.5 8m12.5-8l3.5 8m-9.75-8l-1 8m4.5-8l1 8m-12.25 0h19");
}

</style>
