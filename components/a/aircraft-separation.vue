<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oc1k_h93x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:aircraft-separation" /></template>
<style>
.oc1k_h93x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 3v10m-4-3.5l4-2l4 2m-6 3.5l2-1.5l2 1.5m9-10v10m-4-3.5l4-2l4 2m-6 3.5l2-1.5l2 1.5M3 18.5h18m-16-2l-2 2l2 2m14-4l2 2l-2 2");
}

</style>
