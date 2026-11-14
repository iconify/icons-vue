<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szrkjbbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bonsai-tree" /></template>
<style>
.szrkjbbwk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 16h16l-1.5 5h-13Zm8 0c0-2.5-3.5-2-5-4m5 4c.5-4 4.5-4.5 5-8.5M2.5 12A2.5 2.5 0 0 1 5 9.5a2.75 2.75 0 0 1 5 .5a2 2 0 0 1 .5 2Zm11-4.5A2.5 2.5 0 0 1 16 5a2.75 2.75 0 0 1 5 .5a2 2 0 0 1 .5 2Z");
}

</style>
