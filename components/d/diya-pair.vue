<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nn-xy2giw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:diya-pair" /></template>
<style>
.nn-xy2giw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14.5h8c0 3-1.75 5-4 5s-4-2-4-5Zm11 0h8c0 3-1.75 5-4 5s-4-2-4-5Zm-11 5h19m-15-15c2 3 2.25 4.5 2.25 5a2.25 2.25 0 0 1-4.5 0c0-.5.25-2 2.25-5Zm11 0c2 3 2.25 4.5 2.25 5a2.25 2.25 0 0 1-4.5 0c0-.5.25-2 2.25-5Z");
}

</style>
