<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="otky1blqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cursor-grab" /></template>
<style>
.otky1blqi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 13.5v-5a1.5 1.5 0 0 1 3 0V6a1.5 1.5 0 0 1 3 0v.5a1.5 1.5 0 0 1 3 0v2a1.5 1.5 0 0 1 3 0V15c0 3.6-2.4 6-5.5 6h-1c-1.9 0-3.2-.9-4.25-2.5L4 14.5a1.5 1.5 0 0 1 2-1Zm3-5v3m3-5v5m3-3v3");
}

</style>
