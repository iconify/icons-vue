<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pqb4_4b7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:farm-income" /></template>
<style>
.pqb4_4b7l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 4h12v4.5H7ZM5 8.5h12V13H5Zm8.9 9H3V13h12v2.6m1 5.9c0-4 2-5.5 5.5-5.5c0 3.5-2 5.5-5.5 5.5Zm0 0l3-3");
}

</style>
