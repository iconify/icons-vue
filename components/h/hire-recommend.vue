<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xikjb8bee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hire-recommend" /></template>
<style>
.xikjb8bee {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10.5h4v10h-4Zm4 .5l3.75-6.75c.5-1 2.75-.75 2.75 1.25v4h5.75a2 2 0 0 1 2 2.25l-1.25 7a2 2 0 0 1-2 1.75h-11Z");
}

</style>
