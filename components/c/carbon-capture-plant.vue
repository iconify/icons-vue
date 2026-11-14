<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uf5rk13ef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:carbon-capture-plant" /></template>
<style>
.uf5rk13ef {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 21v-8.5l5-3v3l5-3v3h2.5V9h5v12Zm3.5-4.5V18m4-1.5V18M18 2.5v3.75M16.25 4.5L18 6.25l1.75-1.75");
}

</style>
