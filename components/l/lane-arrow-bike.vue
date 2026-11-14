<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g4x-18bqx"/><path class="tblunablv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lane-arrow-bike" /></template>
<style>
.g4x-18bqx {
  d: path("M12 9.5v-7M8.5 6L12 2.5L15.5 6M3 17a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm11 0a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Z");
}

.tblunablv {
  d: path("m6.5 17l3-4.5h6l2 4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
