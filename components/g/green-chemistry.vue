<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7o771bww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:green-chemistry" /></template>
<style>
.p7o771bww {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 8v3l-5 9a1 1 0 0 0 1 1.5h12a1 1 0 0 0 1-1.5l-5-9V8m-2 0c0-3.5 2.5-5.5 6.5-5.5C18.5 6 16 8 12 8Zm-4.5 7.5h9");
}

</style>
