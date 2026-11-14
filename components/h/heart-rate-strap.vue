<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zfkym72dm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:heart-rate-strap" /></template>
<style>
.zfkym72dm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.1 15H2.5V9h1.2m16.6 0h1.2v6h-2.6M12 18.5c-3-2.5-5.5-4.75-5.5-8a3 3 0 0 1 5.5-2a3 3 0 0 1 5.5 2c0 3.25-2.5 5.5-5.5 8Z");
}

</style>
