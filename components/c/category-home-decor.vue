<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bua2tjetc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:category-home-decor" /></template>
<style>
.bua2tjetc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 10h5m-4 0v2.75C5 13.75 5 21.5 10 21.5h4c5 0 5-7.75-.5-8.75V10M12 2v8m0-4.75c-2.5 0-4.5-.75-5-2.75c2.5 0 4.5.75 5 2.75Zm0 2c2.5 0 4.5-1 5-3c-2.5 0-4.5 1-5 3Z");
}

</style>
