<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fecgtabsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:contract-handshake" /></template>
<style>
.fecgtabsj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7.5H6v8H2.5Zm15.5 0h3.5v8H18ZM6 9l3.5-3H13l5 3M6 14l4.5 3.5q1.5.75 3 0L18 14M9.5 6l4 4M10 11l2.75 2.75");
}

</style>
