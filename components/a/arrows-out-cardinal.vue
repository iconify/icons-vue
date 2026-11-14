<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttz17ybpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:arrows-out-cardinal" /></template>
<style>
.ttz17ybpx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12h.01M8.5 12h-6m3-3l-3 3l3 3m10-3h6m-3-3l3 3l-3 3M12 8.5v-6m3 3l-3-3l-3 3m3 10v6m3-3l-3 3l-3-3");
}

</style>
