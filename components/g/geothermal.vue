<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iol-kgb5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:geothermal" /></template>
<style>
.iol-kgb5c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 15h6l2 4l2-4h9M17 15V9h4.5M9 12c-1.5-2.5 1.5-4.5 0-7.5m3.5 7.5c-1.5-2.5 1.5-4.5 0-7.5");
}

</style>
