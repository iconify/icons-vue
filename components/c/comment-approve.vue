<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wg5714-es"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:comment-approve" /></template>
<style>
.wg5714-es {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 17a8.5 8.5 0 1 1 15.5-4.75h-6.25a2 2 0 0 0-2 2v6.25a8.5 8.5 0 0 1-4.75-1l-3.5 1Zm10.25 1L17 19.75l4-4");
}

</style>
