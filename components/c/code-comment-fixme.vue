<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yboio7buw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:code-comment-fixme" /></template>
<style>
.yboio7buw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.6 20.5H3.5v-18H18v9.1M7 15.5l3-8m1 8l3-8m5.5 6.75a2.5 2.5 0 1 0 2.25 2.25m-4.25 2L15 21");
}

</style>
