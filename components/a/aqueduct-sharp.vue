<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmeyjobkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:aqueduct-sharp" /></template>
<style>
.gmeyjobkd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 6.75h18V14h-1.5v7.25h-3V14h-3v7.25h-3V14h-3v7.25h-3V14H3ZM3 11h18M2.75 3.75c1.156 0 1.156-1 2.313-1s1.156 1 2.312 1s1.156-1 2.313-1s1.156 1 2.312 1s1.156-1 2.313-1s1.156 1 2.312 1s1.156-1 2.313-1s1.156 1 2.312 1");
}

</style>
