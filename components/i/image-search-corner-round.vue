<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zj2anib2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-search-corner-round" /></template>
<style>
.zj2anib2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 21H7a4 4 0 0 1-4-4V7a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4v4M3 17l4-4a2.83 2.83 0 0 1 4 0m3-5a1 1 0 1 0 2 0a1 1 0 0 0-2 0m1 9a2 2 0 1 0 4 0a2 2 0 0 0-4 0m4 2l2 2");
}

</style>
