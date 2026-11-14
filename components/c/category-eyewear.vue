<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kie7-y_-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:category-eyewear" /></template>
<style>
.kie7-y_-a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 14a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0m11 0a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0m-3.5 0c.75-1.5 2.75-1.5 3.5 0m-11 0V9m18.5 5V9");
}

</style>
