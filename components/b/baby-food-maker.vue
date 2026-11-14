<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tgw919t_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:baby-food-maker" /></template>
<style>
.tgw919t_e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 2.5h12v3H6Zm2.25 13l-1.5-10m10.5 0l-1.5 10m-10.25 6h13V18c0-1.5-1-2.5-2.5-2.5H8c-1.5 0-2.5 1-2.5 2.5Zm6.5-3h.01");
}

</style>
