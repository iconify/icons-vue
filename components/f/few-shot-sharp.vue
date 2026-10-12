<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jh3krrcpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:few-shot-sharp" /></template>
<style>
.jh3krrcpr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h7v4.5h-7zm0 7h7v4.5h-7zm0 7h7v4.5h-7zm9-11.75H13v7h1.5H13v7h-1.25m6.5-10l.36 2.64l2.64.36l-2.64.36l-.36 2.64l-.36-2.64l-2.64-.36l2.64-.36z");
}

</style>
