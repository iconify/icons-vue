<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1umcuvph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:jar-mug" /></template>
<style>
.w1umcuvph {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 3h11v4h-11ZM4 7h12v14.5H4Zm12 3h1.5a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H16m-9-7.5V17");
}

</style>
