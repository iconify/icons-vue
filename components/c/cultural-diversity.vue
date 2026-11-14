<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwzlkrbxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cultural-diversity" /></template>
<style>
.vwzlkrbxs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 7.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM6.5 21c0-3.5 2.5-6.5 5.5-6.5s5.5 3 5.5 6.5m-15-10.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm0 9c0-2.25 1.25-4 3-4m11.75-5a2 2.5 0 1 0 4 0a2 2.5 0 1 0-4 0Zm4.25 9c0-2.25-1.25-4-3-4");
}

</style>
