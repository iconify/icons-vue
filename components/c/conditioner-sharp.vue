<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="srliyxanz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:conditioner-sharp" /></template>
<style>
.srliyxanz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 2.75h5V5.5h-5zM3.75 8.5h8.5v12.75h-8.5zm14-3.75c2.5 2.5 2.5 4.5 0 7s-2.5 4.5 0 7");
}

</style>
