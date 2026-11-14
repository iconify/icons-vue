<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mmtva0b_i"/><path class="fuio79b1o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:directions" /></template>
<style>
.fuio79b1o {
  d: path("M9.75 8.25L8 10l1.75 1.75m4.5-3.5L16 10l-1.75 1.75");
}

.mmtva0b_i {
  d: path("M12 2.25L21.75 12L12 21.75L2.25 12Zm0 14.25V10m-4 0h8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
