<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a1bo0ubjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:capacity-empty" /></template>
<style>
.a1bo0ubjj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8h16v8h-16Zm16 2H20a1.5 1.5 0 0 1 1.5 1.5v1A1.5 1.5 0 0 1 20 14h-1.5");
}

</style>
