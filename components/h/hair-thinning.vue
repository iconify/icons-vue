<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="otbv6w5xe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hair-thinning" /></template>
<style>
.otbv6w5xe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 3C3.5 9 8.5 14 6 21m4.5-18C8 9 13 14 10.5 21M15 3c-2.18 4.36.963 6.059.477 8.743m-.249.804q-.096.22-.228.453m3 1.5v7m-3-3l3 3l3-3");
}

</style>
