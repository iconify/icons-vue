<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zkbwiibjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:espresso-cup" /></template>
<style>
.zkbwiibjm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 5.5h12v6A5.5 5.5 0 0 1 11 17h-1a5.5 5.5 0 0 1-5.5-5.5ZM3 17h18q-1.5 2.5-4 2.5H7q-2.5 0-4-2.5Zm13.5-9.5h1a2.5 2.5 0 0 1 0 5h-1");
}

</style>
