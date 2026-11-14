<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jueitd_6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:iguana" /></template>
<style>
.jueitd_6e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 17.5q3-3 6.5-3h11l1.5-3l-2.5-3h-2.5l-1-2.5l-1 2.5l-1-2.5l-1 2.5l-1-2.5l-1 2.5l-1-2.5l-1 2.5q-3.5 1-6 9Zm16-6.75h.01M9.5 14.5l-2 4m2-4l2 4m5-4l-2 4m2-4l2 4");
}

</style>
