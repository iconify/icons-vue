<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="brk4pbmcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:car-battery-sharp" /></template>
<style>
.brk4pbmcu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7.25h18.5v13H2.75zM5 4.5h3.5v2.75H5zm10.5 0H19v2.75h-3.5zM5.25 13.75h3.5M7 12v3.5m8.25-1.75h3.5");
}

</style>
