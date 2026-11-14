<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x59tq3pzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hurricane-glass" /></template>
<style>
.x59tq3pzu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 2.5h8c0 2.5-1.25 4-1.25 6s2.25 3 2.25 6c0 2-2 3.5-5 3.5s-5-1.5-5-3.5c0-3 2.25-4 2.25-6S8 5 8 2.5ZM12 18v3.5m-3 0h6");
}

</style>
