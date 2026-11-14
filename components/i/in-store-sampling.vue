<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jormmq4vo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:in-store-sampling" /></template>
<style>
.jormmq4vo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 16.5h18c-.5 2.75-4 4.5-9 4.5s-8.5-1.75-9-4.5Zm1.5-4h4v4h-4Zm5.5 0h4v4h-4Zm5.5 0h4v4h-4Zm-9 0L5 7.5m7 5v-6m5.5 6l1.5-5");
}

</style>
