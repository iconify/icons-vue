<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d4dp9fbey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fiber-bundle" /></template>
<style>
.d4dp9fbey {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 6H9v12H5.5Zm-3 3h3m-3 3h3m-3 3h3M9 9h2c4 0 5-4.5 10-4.5M9 12h12M9 15h2c4 0 5 4.5 10 4.5");
}

</style>
