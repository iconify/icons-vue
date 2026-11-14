<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hd2v7756z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lab-shaker" /></template>
<style>
.hd2v7756z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 3v5.5l-4 8h11l-4-8V3m-4 0h5M4 19.75h16M20 7a6 6 0 0 1 0 8M4 7a6 6 0 0 0 0 8");
}

</style>
