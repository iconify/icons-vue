<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-mir-b1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:headset-mic" /></template>
<style>
.i-mir-b1j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 12v-.5a7 7 0 0 1 14 0v.5M3 12h5v6.5H3Zm13 0h5v6.5h-5Zm2.5 6.5v.5a2.5 2.5 0 0 1-2.5 2.5h-3.5");
}

</style>
