<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k35u_1bzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:avalanche-shovel" /></template>
<style>
.k35u_1bzw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 14.5h8v4c0 2-2 3-4 3s-4-1-4-3Zm4-9v9m-2.5-12h5v3h-5Zm1.25 7.5h2.5");
}

</style>
