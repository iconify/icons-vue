<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfogimb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:aroma-diffuser" /></template>
<style>
.yfogimb2m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 9.5h4V12h2a2 2 0 0 1 2 2v5.5a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2V14a2 2 0 0 1 2-2h2Zm1 0l-5-6m7 6l5-6m-6 3c-1.25-1 1.25-2.5 0-3.5");
}

</style>
