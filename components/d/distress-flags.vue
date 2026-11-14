<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zif794byu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:distress-flags" /></template>
<style>
.zif794byu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 2.5v19m0-18.5h7.5v7.5h-7.5Zm0 10.25h7.5v7.5h-7.5Zm0-2.75l7.5-7.5m-7.5 17.75l7.5-7.5");
}

</style>
