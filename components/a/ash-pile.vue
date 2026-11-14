<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tthwj4_sv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ash-pile" /></template>
<style>
.tthwj4_sv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20c1-3.5 3-5 5.5-5c.5-3 2-4.5 4-4.5c2.5 0 4 2 4.5 4c2.5 0 4.5 2.5 5 5.5ZM11 7.5q-1.5-1.75.5-2.75t1-2.25M9.5 17h.01m5.49.5h.01");
}

</style>
