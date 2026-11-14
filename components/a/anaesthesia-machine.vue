<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbk2d0irm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:anaesthesia-machine" /></template>
<style>
.nbk2d0irm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 7h4a1 1 0 0 1 1 1v12.5a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V8a1 1 0 0 1 1-1Zm2 0V3M5 3h4m0 0c6 0 8 3 8 8.5m-3.5 0h7l-1.25 4c-.5 1.75-4 1.75-4.5 0Z");
}

</style>
