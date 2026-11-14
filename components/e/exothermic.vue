<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ndzc6mtki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:exothermic" /></template>
<style>
.ndzc6mtki {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 9v2.75a5 5 0 1 0 3 0V9M8 6.25q-1-1 0-2T8 2.5m4 3.75q-1-1 0-2t0-1.75m4 3.75q-1-1 0-2t0-1.75");
}

</style>
