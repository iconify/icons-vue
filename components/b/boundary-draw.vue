<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzb83bb6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:boundary-draw" /></template>
<style>
.lzb83bb6x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 5h6.25l2 9.5H2.5Zm11.5 13.75l-.25-3.25L19 10l3 1.5l-2.75 5.5Zm-14 0h14m-.25-3.25l3 1.5");
}

</style>
