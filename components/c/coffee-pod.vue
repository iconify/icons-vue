<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qp067acer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coffee-pod" /></template>
<style>
.qp067acer {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7 15l1.5-8a2 2 0 0 1 2-2h3a2 2 0 0 1 2 2l1.5 8M4 15h16v3H4Zm10.5 3q4 0 6 3");
}

</style>
