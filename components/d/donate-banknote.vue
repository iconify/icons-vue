<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="em4j34a7u"/><path class="syjwo5ble"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:donate-banknote" /></template>
<style>
.em4j34a7u {
  d: path("M2.5 6h19v12h-19Z");
}

.syjwo5ble {
  d: path("M9 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm-3 0h.01M18 12h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
