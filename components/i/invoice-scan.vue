<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7glgsbqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:invoice-scan" /></template>
<style>
.s7glgsbqs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 2.5h13V21l-2.25-1.5L14 21l-2-1.5l-2 1.5l-2.25-1.5L5.5 21Zm3 4.5h7m-7 9H13M2.5 11.5h19");
}

</style>
