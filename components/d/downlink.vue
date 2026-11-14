<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3gcfqb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:downlink" /></template>
<style>
.d3gcfqb2t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.211 13.445l-2.474 2.474l-5.656-5.656l3.182-3.182l4.95 4.95M2.308 16.45l3.889-3.889l4.242 4.242l-3.889 3.889ZM12.561 6.197l3.889-3.889l4.242 4.242l-3.889 3.889ZM8.25 14.75L10 13m3-3l1.75-1.75M4.25 14.5l4.25 4.25m6-14.5l4.25 4.25m-.75 6v7m-3-3l3 3l3-3");
}

</style>
