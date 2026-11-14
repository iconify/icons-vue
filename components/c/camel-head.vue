<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfjz3twpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:camel-head" /></template>
<style>
.yfjz3twpa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8.25c1-1.75 4-4.25 7-5l.75-.75L11 4c.75 1.5 1 4 1.5 6.5q.75 3 2.25 3c.75-2.5 1.75-5 3.5-5c2 0 3.25 2.5 3.25 6v7H10.75c0-5-.75-8.75-2.75-11.25c-1.5 0-2.25.5-3.25.5s-1.5-.75-1.5-1.5c-.5 0-.75-.5-.75-1Zm5-1.5h.01");
}

</style>
