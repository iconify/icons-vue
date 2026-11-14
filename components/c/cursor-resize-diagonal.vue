<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pb3m5zrul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cursor-resize-diagonal" /></template>
<style>
.pb3m5zrul {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.282 5.282h7.072l-2.122 2.122l6.364 6.364l2.122-2.122v7.072h-7.072l2.122-2.122l-6.364-6.364l-2.122 2.122Z");
}

</style>
