<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k2iq4vn4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:light-ray" /></template>
<style>
.k2iq4vn4w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 19a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm6.25-3.75L21 3m-6.75 11.25l5-5m-9.5.5l5-5");
}

</style>
