<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y8v8u4iyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bbq-area" /></template>
<style>
.y8v8u4iyd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 10a6 6 0 1 0 12 0a6 6 0 1 0-12 0Zm0 0h12m-9.5 7L7 21m8.5-4l1.5 4m-5-5v5");
}

</style>
