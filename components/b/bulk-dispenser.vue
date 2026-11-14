<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-2tabbhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bulk-dispenser" /></template>
<style>
.y-2tabbhw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 2.5h13v7l-5 4v2h-3v-2l-5-4Zm0 3h13M8 18.5h8c0 1.75-1.5 3-4 3s-4-1.25-4-3Zm8 0h4.5");
}

</style>
