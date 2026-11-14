<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxj09xb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drizzle" /></template>
<style>
.wxj09xb-n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 15h11a3.5 3.5 0 0 0 0-7A5.5 5.5 0 0 0 7 9a3.25 3.25 0 0 0-.5 6Zm2 2.75l-1 3m5-3l-1 3m5-3l-1 3");
}

</style>
