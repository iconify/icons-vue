<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tn1qywuyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gi-collar-grip" /></template>
<style>
.tn1qywuyw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21.5V10c0-3 2-5 5.5-6.5m13.5 18V10c0-3-2-5-5.5-6.5m-8 0l3 7.5m5-7.5L13 11m-4 0h6v5.5H9Zm1.5 5.5v5m3-5v5");
}

</style>
