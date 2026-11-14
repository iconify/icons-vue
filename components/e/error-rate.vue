<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lc_wrqbrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:error-rate" /></template>
<style>
.lc_wrqbrd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.523 18.5H2L11 3l5.624 9.686M11 8.5v4m0 2.75h.01m3.74 6l6.5-6.5m-5.75.75h.01m4.99 5h.01");
}

</style>
