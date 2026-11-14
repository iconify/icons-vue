<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xttn5-t6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gadget-water-damage" /></template>
<style>
.xttn5-t6g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 2.5H13v19H3.5Zm3 16H10M18 7s3 3.5 3 6a3 3 0 0 1-6 0c0-2.5 3-6 3-6Z");
}

</style>
