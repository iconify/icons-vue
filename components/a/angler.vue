<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_v5p0byc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:angler" /></template>
<style>
.d_v5p0byc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 19.5c0-3.25 3.25-5.5 7.5-5.5s7.5 2.25 7.5 5.5c0 .6-.4 1-1 1H4c-.6 0-1-.4-1-1ZM6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm7 10.5l6-14.5m0 0v8a1.25 1.25 0 0 0 2.5 0");
}

</style>
