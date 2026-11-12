<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-5khebak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:boolean-intersect" /></template>
<style>
.k-5khebak {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 10a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1ZM3 7V4a1 1 0 0 1 1-1h3m4 0h3a1 1 0 0 1 1 1v1M3 11v3a1 1 0 0 0 1 1h1m14-6h1a1 1 0 0 1 1 1v3m0 4v3a1 1 0 0 1-1 1h-3m-8-2v1a1 1 0 0 0 1 1h3");
}

</style>
