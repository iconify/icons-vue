<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jg8kaqblr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:booklet" /></template>
<style>
.jg8kaqblr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 4.5l9 2.25V21.5l-9-2.25Zm9 2.25l9-2.25v14.75l-9 2.25Zm-6 2.5L9 10m6 0l3-.75");
}

</style>
