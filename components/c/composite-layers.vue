<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0lht_btl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:composite-layers" /></template>
<style>
.a0lht_btl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 3.25l8.5 4.25l-8.5 4.25L3.5 7.5ZM3.5 12l8.5 4.25L20.5 12m-17 4.5l8.5 4.25l8.5-4.25m-10-9.75l3 1.5");
}

</style>
