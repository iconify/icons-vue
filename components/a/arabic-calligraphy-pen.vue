<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvvhqkdde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:arabic-calligraphy-pen" /></template>
<style>
.vvvhqkdde {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17.5 3.5l3 3l-10 10l-5.5 2l2.5-5Zm-2 12.5s2.25 2.5 2.25 3.75a2.25 2.25 0 0 1-4.5 0c0-1.25 2.25-3.75 2.25-3.75Z");
}

</style>
