<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jz9iiuoav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:joggers" /></template>
<style>
.jz9iiuoav {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 2.5h14v3H5Zm1 3L6.5 18H10l2-9l2 9h3.5L18 5.5M6.5 18H10v3.5H6.5Zm7.5 0h3.5v3.5H14Z");
}

</style>
