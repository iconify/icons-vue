<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hnw43ubaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:crocus" /></template>
<style>
.hnw43ubaa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 3c-1 5 .5 9 3.5 9s4.5-4 3.5-9C14 4 13 5.5 12 8c-1-2.5-2-4-3.5-5Zm3.5 9v8m0 0c-2.5-2-5-4-6.5-7.5M12 20c2.5-2 5-4 6.5-7.5M4.5 20h15");
}

</style>
