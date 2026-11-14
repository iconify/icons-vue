<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nrgzeqvxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:campaign-new" /></template>
<style>
.nrgzeqvxe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.525 15.215L6.5 11H3V7h3.5L14 2.5v12.654M5.5 11l1 4M17 6l2.5-1.5m-2 5h3M18 15v6m-3-3h6");
}

</style>
