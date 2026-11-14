<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6jmf5bkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:base-steal" /></template>
<style>
.k6jmf5bkz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16 6.5l5.5 5.5l-5.5 5.5l-5.5-5.5ZM2.5 12h5.25M5 9.25L7.75 12L5 14.75");
}

</style>
