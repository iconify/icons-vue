<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uxwth_b7u"/><path class="bjeltsb8w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bin-picking" /></template>
<style>
.bjeltsb8w {
  d: path("M6.5 16.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm7 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM12 2.5V6M8 9.5L9.5 6h5L16 9.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uxwth_b7u {
  d: path("M3.5 11.5V19a2 2 0 0 0 2 2h13a2 2 0 0 0 2-2v-7.5");
}

</style>
