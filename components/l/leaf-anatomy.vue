<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nzv9_g17j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:leaf-anatomy" /></template>
<style>
.nzv9_g17j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 19C3 10 10 3.5 20 4c.5 10-6 17-15 15Zm-2 2L16 8m-8 8h3m0-3v-3m3 0h2.5");
}

</style>
