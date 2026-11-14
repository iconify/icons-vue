<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yeqlgqvhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cabaret-layout" /></template>
<style>
.yeqlgqvhy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 9.25a5 5 0 1 0 10 0a5 5 0 1 0-10 0ZM9.75 17h4.5v4.5h-4.5Zm8.75-4.432l3.182 3.182l-3.182 3.182l-3.182-3.182Zm-13 0l3.182 3.182L5.5 18.932L2.318 15.75Z");
}

</style>
