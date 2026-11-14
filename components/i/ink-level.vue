<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="objucxb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ink-level" /></template>
<style>
.objucxb4d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12.75a9.5 9.5 0 0 1 19 0m-9.5 0l3.75-5M12 15.5s-2.5 1.5-2.5 3a2.5 2.5 0 0 0 5 0c0-1.5-2.5-3-2.5-3Z");
}

</style>
