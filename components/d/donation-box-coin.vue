<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5-4nz96n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:donation-box-coin" /></template>
<style>
.o5-4nz96n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 11.75H5.5a2 2 0 0 0-2 2V19a2 2 0 0 0 2 2h13a2 2 0 0 0 2-2v-5.25a2 2 0 0 0-2-2H14v2h-4ZM8.5 5.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0ZM12 4v3");
}

</style>
