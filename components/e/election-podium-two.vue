<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxe6fl1sz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:election-podium-two" /></template>
<style>
.wxe6fl1sz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 15.5h7.75v6H2.5Zm11.25 0h7.75v6h-7.75ZM4 4.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm11.5 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm-12.5 8c0-1.75 1.5-3 3.25-3s3.25 1.25 3.25 3m5 0c0-1.75 1.5-3 3.25-3S21 11 21 12.75");
}

</style>
