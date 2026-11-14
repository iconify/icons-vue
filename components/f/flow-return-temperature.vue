<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovllelbdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flow-return-temperature" /></template>
<style>
.ovllelbdj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 5H21m-2.25-2.25L21 5l-2.25 2.25M3 12.5h11m-8.75-2.25L3 12.5l2.25 2.25M17 17.25v-3a1.25 1.25 0 0 1 2.5 0v3a2.25 2.25 0 1 1-2.5 0Z");
}

</style>
