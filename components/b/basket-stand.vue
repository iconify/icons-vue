<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivgsoqult"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:basket-stand" /></template>
<style>
.ivgsoqult {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13h19l-2 8.5h-15Zm.5 0l-.5-3.5h19L21 13M3 9.5L2.5 6h19L21 9.5M7 6l2.5-3.5M17 6l-2.5-3.5M8 15.5V19m4-3.5V19m4-3.5V19");
}

</style>
