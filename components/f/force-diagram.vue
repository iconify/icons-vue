<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="np_qau8df"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:force-diagram" /></template>
<style>
.np_qau8df {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 8.5h7v7h-7Zm3.5 0V3m-2 2l2-2l2 2m1.5 7H21m-2-2l2 2l-2 2m-7 1.5V21m-2-2l2 2l2-2m-5.5-7H3m2-2l-2 2l2 2");
}

</style>
