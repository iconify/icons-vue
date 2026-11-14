<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qa4i0yyxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cream-jug" /></template>
<style>
.qa4i0yyxg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 7h10l-1 10.5c-.2 1.5-1.5 2.5-3 2.5h-2c-1.5 0-2.8-1-3-2.5Zm10 2.5c3 0 3.5 5-.5 5M7 7c1-2.5 2.5-2.5 3.5 0");
}

</style>
