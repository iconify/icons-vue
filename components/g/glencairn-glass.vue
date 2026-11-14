<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a5xbu_bvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:glencairn-glass" /></template>
<style>
.a5xbu_bvw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 3h5c0 3 2.5 5.5 2.5 9.5c0 3-2 4.5-5 4.5s-5-1.5-5-4.5C7 8.5 9.5 6 9.5 3ZM12 17v2m-4 0h8v2.5H8Z");
}

</style>
