<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vp450hb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lab-glassware-icon" /></template>
<style>
.vp450hb6l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9v9.5a1.5 1.5 0 0 0 3 0V9M11 3.5v6l-2.5 9.75a1 1 0 0 0 1 1.25h5a1 1 0 0 0 1-1.25L13 9.5v-6M18.5 9v11.5h3V9");
}

</style>
