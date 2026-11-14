<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3qvuebvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ai-safety" /></template>
<style>
.p3qvuebvm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.7 17H3.5V6h14v4.7m-7-7.7v3M8 10v2.5m5-2.5v2.3m5 1.2l3.5 1.25v2.75c0 2-1.5 3.25-3.5 4c-2-.75-3.5-2-3.5-4v-2.75Z");
}

</style>
