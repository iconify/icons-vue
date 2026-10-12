<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6zx1zbbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:feast-table-sharp" /></template>
<style>
.y6zx1zbbi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 14.25h18.5m-17.75 0v7m17-7v7m-14.75-7a4.25 4.25 0 0 1 8.5 0M10 10V8m6.25-1.5h3.5v4.25h-3.5V9ZM18 10.75v3.5");
}

</style>
