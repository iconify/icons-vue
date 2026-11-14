<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hro631bab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ceramic-mug" /></template>
<style>
.hro631bab {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 4h12v12a4 4 0 0 1-4 4H8a4 4 0 0 1-4-4Zm12 4h1.5a3 3 0 0 1 3 3v1a3 3 0 0 1-3 3H16");
}

</style>
