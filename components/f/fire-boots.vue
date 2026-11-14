<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vs53ywzvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fire-boots" /></template>
<style>
.vs53ywzvs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 2.5h6V6h-6ZM10 6v15H4a1.5 1.5 0 0 1-1.5-1.5V19a3 3 0 0 1 3-3V6m7.75-3.5h6V6h-6ZM14 6v15h6a1.5 1.5 0 0 0 1.5-1.5V19a3 3 0 0 0-3-3V6");
}

</style>
