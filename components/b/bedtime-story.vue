<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jzvxy1bag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bedtime-story" /></template>
<style>
.jzvxy1bag {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21c-2-1.25-5.5-1.75-9.5-1.25V12.5c4-.5 7.5 0 9.5 1.5c2-1.5 5.5-2 9.5-1.5v7.25c-4-.5-7.5 0-9.5 1.25Zm0-7v7m1.75-18a3.5 3.5 0 1 0 1.75 5.25A3.25 3.25 0 0 1 13.75 3Z");
}

</style>
