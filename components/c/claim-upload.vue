<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crdf88pja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:claim-upload" /></template>
<style>
.crdf88pja {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12h5l1.5 2.5h5L16 12h5v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Zm9-8.5v7m-3-4l3-3l3 3");
}

</style>
