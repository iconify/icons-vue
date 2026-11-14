<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zalm3ub0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lat-pulldown" /></template>
<style>
.zalm3ub0t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 3.5h12m-9 3a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm3 3v7m-9 4l1.5-4h15l1.5 4");
}

</style>
