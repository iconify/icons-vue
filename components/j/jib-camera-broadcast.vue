<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dz33d_emn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:jib-camera-broadcast" /></template>
<style>
.dz33d_emn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 18l12-9m-8 6l-3 6.5M7 15l3 6.5m4-17h5.5V9H14Zm5.5 1l2-1V9l-2-1Z");
}

</style>
