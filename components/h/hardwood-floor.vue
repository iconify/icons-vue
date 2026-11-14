<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="skt4hqb9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hardwood-floor" /></template>
<style>
.skt4hqb9f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 4h10l4.5 16h-19Zm3.25 0l-1.5 16m5-16l1.5 16m-11-6h5m.5-5h4.5m.25 3h4.75");
}

</style>
