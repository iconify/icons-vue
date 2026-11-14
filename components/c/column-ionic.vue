<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="znn1cy1xi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:column-ionic" /></template>
<style>
.znn1cy1xi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 8.5A2.5 2.5 0 1 1 8 6h8a2.5 2.5 0 1 1 2.5 2.5M8 6v11.5M16 6v11.5m-11.5 0h15v3h-15Z");
}

</style>
