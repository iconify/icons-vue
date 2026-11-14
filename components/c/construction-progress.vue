<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uyxb9-bva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:construction-progress" /></template>
<style>
.uyxb9-bva {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 15.5h17a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-17a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1Zm.5-8h5v5H4Zm5 0h5v5H9Zm-2.5-5h5v5h-5Zm-1 16h9");
}

</style>
