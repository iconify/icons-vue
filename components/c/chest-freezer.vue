<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_qjif_sr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chest-freezer" /></template>
<style>
.w_qjif_sr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10.5h19v11h-19Zm-.348-4.976L20.967 2.88l.348 2.476L2.5 8ZM12 13.25v5.5M9.5 14.5l5 3m-5 0l5-3");
}

</style>
