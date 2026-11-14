<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2lt0xrbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bottle-glass-grocery" /></template>
<style>
.f2lt0xrbx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 5.5v2q-3 2-3 5V20a1.5 1.5 0 0 0 1.5 1.5h7A1.5 1.5 0 0 0 17 20v-7.5q0-3-3-5v-2Zm-.5-3h5v3h-5ZM7 13h10M7 18h10");
}

</style>
