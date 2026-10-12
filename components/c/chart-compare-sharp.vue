<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vslhzqlxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chart-compare-sharp" /></template>
<style>
.vslhzqlxy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 8.75h5v11.5h-5zm11.5-4h5v15.5h-5zM10 9h4m-1.5-1.5L14 9l-1.5 1.5M14 14h-4m1.5-1.5L10 14l1.5 1.5");
}

</style>
