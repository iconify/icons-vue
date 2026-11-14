<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6xszyo-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cheque-book" /></template>
<style>
.h6xszyo-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7.5h19v12h-19Zm1.5 0v-3a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v3M7 10.25V12m0 2.75v1.75m3-3h7");
}

</style>
