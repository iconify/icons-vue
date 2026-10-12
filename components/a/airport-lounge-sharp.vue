<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cyd2_cbps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:airport-lounge-sharp" /></template>
<style>
.cyd2_cbps {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 6h8M13 6l-2.25-3.25M13 6l-2.25 3.25M9.25 6l-1-1.5m1 1.5l-1 1.5M2.75 13v-1.75h3.5v3.25h11.5v-3.25h3.5V20H2.75v-2Zm2.75 7v1.25m13-1.25v1.25");
}

</style>
