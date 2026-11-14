<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w7v1zgbmc"/><path class="claz6zbjh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:graphql-query" /></template>
<style>
.claz6zbjh {
  d: path("M8.5 7c-1.25 0-1.25.5-1.25 1.5v.75c0 .75-.5 1.25-1.25 1.25c.75 0 1.25.5 1.25 1.25v.75c0 1 0 1.5 1.25 1.5m4-7c1.25 0 1.25.5 1.25 1.5v.75c0 .75.5 1.25 1.25 1.25c-.75 0-1.25.5-1.25 1.25v.75c0 1 0 1.5-1.25 1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w7v1zgbmc {
  d: path("M3 10.5a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0Zm12.75 5.25L21 21");
}

</style>
