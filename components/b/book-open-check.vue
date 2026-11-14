<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ij_51wb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:book-open-check" /></template>
<style>
.ij_51wb6a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M21 11.767V4.5q-6-.75-9 1.5q-3-2.25-9-1.5v14q6-.75 9 1.5a7 7 0 0 1 .48-.329M12 6v10.8m0 2.4v.8m2.75-2l2 2L21 15.75");
}

</style>
