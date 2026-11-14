<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydu7371xg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:currency-exchange" /></template>
<style>
.ydu7371xg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 3.5H5.75a1.75 1.75 0 0 0 0 3.5h1.5a1.75 1.75 0 0 1 0 3.5H3.5m3-8v9m6.5 5.75a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0ZM13 4.5h3.5A2.5 2.5 0 0 1 19 7v2.75m-2-2l2 2l2-2M10.5 19.5h-3A2.5 2.5 0 0 1 5 17v-2.25m-2 2l2-2l2 2");
}

</style>
