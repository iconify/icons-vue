<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f68722bgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:analytics-annotation" /></template>
<style>
.f68722bgy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 13v8m4-17v17m4-12v12m4-7.5h5a1 1 0 0 1 1 1V18a1 1 0 0 1-1 1H18l-2.5 2v-2a1 1 0 0 1-1-1v-3.5a1 1 0 0 1 1-1Z");
}

</style>
