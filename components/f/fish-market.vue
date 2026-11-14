<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwa4vpuav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fish-market" /></template>
<style>
.hwa4vpuav {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4.5h18V8a3 3 0 0 1-6 0a3 3 0 0 1-6 0a3 3 0 0 1-6 0ZM4 11v10m16-10v10M7 13.75L9.75 16c1.75-3 5.75-3 7.25 0c-1.5 3-5.5 3-7.25 0L7 18.25Z");
}

</style>
