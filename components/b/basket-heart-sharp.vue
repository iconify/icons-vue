<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3zw-bb_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:basket-heart-sharp" /></template>
<style>
.x3zw-bb_o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 9.25h15.5l1.276.001l-.306 1.239l-1.85 7.65l-.464 1.91H5.594l-.464-1.91l-1.85-7.65l-.306-1.239zm3.5 0l2.75-5m5.75 5l-2.75-5m-4.75 8.5v3.5m3.25-3.5v3.5m3.25-3.5v3.5");
}

</style>
