<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2739_zgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:back-in-stock" /></template>
<style>
.x2739_zgt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.2 21.5H2.5v-12h11v5.8m-11-5.8H7L5.25 4L2.5 5.25Zm11 0H9L10.75 4l2.75 1.25Zm-11 3h11m1.5 7.25h6.5c-.75-1-1-2-1-2.75a2.25 2.25 0 0 0-4.5 0c0 .75-.25 1.75-1 2.75Zm3.25 1.75h.01");
}

</style>
