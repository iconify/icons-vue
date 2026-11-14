<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_g2vbytu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hand-count-three" /></template>
<style>
.z_g2vbytu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 12.5V6.25a1.75 1.75 0 0 1 3.5 0v-2a1.75 1.75 0 0 1 3.5 0v1a1.75 1.75 0 0 1 3.5 0v5.25h1a2 2 0 0 1 2 2v3c0 3.5-2.75 6-6.5 6h-1c-4 0-7.5-2.5-7.5-6V14A1.5 1.5 0 0 1 6 12.5Zm3.5-6.25v4.25M13 5.25v5.25");
}

</style>
