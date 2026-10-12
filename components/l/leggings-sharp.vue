<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ao6_ovbwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:leggings-sharp" /></template>
<style>
.ao6_ovbwh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 2.75h10l.13.99l.49 3.77q.13.99.09 1.99l-.42 10.75l-.04 1h-2.5l-.3-.96l-2.65-8.58l-.3-.96l-.3.96l-2.65 8.58l-.3.96h-2.5l-.04-1L5.79 9.5q-.04-1 .09-1.99l.49-3.77l.13-.99zM6.15 5.5h11.7");
}

</style>
