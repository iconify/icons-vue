<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8yw9wbre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:anklet" /></template>
<style>
.h8yw9wbre {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 8.5a9 5.5 0 1 0 18 0a9 5.5 0 1 0-18 0Zm9 5.5v1.75m-3 3a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm3 0h.01");
}

</style>
