<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwvoj4bvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:liquid-refill-tap" /></template>
<style>
.iwvoj4bvf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 2.25v4.5M3 3h8.5a2 2 0 0 1 2 2v.75m-3 9.75h6V20a1.5 1.5 0 0 1-1.5 1.5h-3a1.5 1.5 0 0 1-1.5-1.5Zm3-7l1.25 1.75a1.5 1.5 0 1 1-2.5 0Zm3 8h2a2 2 0 0 1 2 2a2 2 0 0 1-2 2h-2");
}

</style>
