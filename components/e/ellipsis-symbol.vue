<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3e4edcdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ellipsis-symbol" /></template>
<style>
.g3e4edcdh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 17a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm6.5 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm6.5 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

</style>
