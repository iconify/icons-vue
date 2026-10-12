<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_evk5bgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:balance-sheet-sharp" /></template>
<style>
.h_evk5bgr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 2.75h16.5v18.5H3.75zm0 5h16.5m-8.25 0v13.5m-5.25-10h2.5m-2.5 3h2.5m5.5-3h2.5m-2.5 3h2.5m-10.5 3.5h2.5m5.5 0h2.5");
}

</style>
