<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdtg04b2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:kid-waving" /></template>
<style>
.wdtg04b2n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 6.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm-3 15C4 17 6.75 14 10.5 14s6.5 3 6.5 7.5M14 15l5.5-9");
}

</style>
