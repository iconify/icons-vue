<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqc7mtrrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:crossplay" /></template>
<style>
.lqc7mtrrj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h11v8h-11Zm3 10.75h5M15 10.5h6.5v11H15Zm1.25-6q2 0 2 3M16.75 6l1.5 1.5l1.5-1.5m-7.5 13.5q-6.75 0-6.75-3M4 18l1.5-1.5L7 18");
}

</style>
