<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="niy_wye5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:beach-access" /></template>
<style>
.niy_wye5b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 8.25a7.5 7.5 0 0 1 14.5 4Zm7.25 2L10 17m-7.5 0h19m-19 3.75q2.25-1.75 4.75 0q2.25 1.75 4.75 0q2.25-1.75 4.75 0q2.25 1.75 4.75 0");
}

</style>
