<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v671x7pou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bulrush" /></template>
<style>
.v671x7pou {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 2.5v2m-2.5 0h5v9h-5Zm2.5 9v8m5.5-13H19v7h-4.5Zm2.25 7v6M9 21.5c-2-2.5-4-4-5-5");
}

</style>
