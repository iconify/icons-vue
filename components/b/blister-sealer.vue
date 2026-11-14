<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mh903pvnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blister-sealer" /></template>
<style>
.mh903pvnt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 11H3a2.5 4.5 0 0 1 5 0h1.5a2.5 4.5 0 0 1 5 0H16a2.5 4.5 0 0 1 5 0h.5m-19 3h19v4h-19Z");
}

</style>
