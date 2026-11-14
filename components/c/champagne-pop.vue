<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrgjcfb2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:champagne-pop" /></template>
<style>
.mrgjcfb2z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.917 6.179l2.166 1.25l-1.75 3.031l.881 3.973l-3.75 6.495l-6.928-4l3.75-6.495l3.881-1.223Zm2.875-4.137l2.166 1.25l-1.25 2.166l-2.166-1.25ZM12.5 3.5h.01M20.5 7h.01");
}

</style>
