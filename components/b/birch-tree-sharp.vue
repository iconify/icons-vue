<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhha3n0oe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:birch-tree-sharp" /></template>
<style>
.uhha3n0oe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.75 21.25l1-17.75v-.75h2.5v.75l1 17.75ZM10.5 8.5H12m2 4.25h-1.75m-2 4.25H12m1.75-7l3.75-3.25m-7 6.75l-4-2.5m11-4.25c.25-1.5 1.5-2.5 3.25-2.5c0 1.75-1.5 2.75-3.25 2.5ZM6.5 11C6.25 9.5 5 8.5 3.25 8.5c0 1.75 1.5 2.75 3.25 2.5Z");
}

</style>
