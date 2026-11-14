<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dumpw-bvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cloud-offline" /></template>
<style>
.dumpw-bvi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.965 18.364a4 4 0 0 1 0-7.728m1.367-1.517a5.5 5.5 0 0 1 7.918-2.882m1.463 1.228a5.5 5.5 0 0 1 1.266 3.056m1 1.307a3.5 3.5 0 0 1-.573 6.553M9.5 18.5h5");
}

</style>
