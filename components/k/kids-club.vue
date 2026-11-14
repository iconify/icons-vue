<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yq5wl7b0u"/><path class="ptp4d6kht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:kids-club" /></template>
<style>
.ptp4d6kht {
  d: path("m14.5 10l2-5.5h3l2 3.5l-2.75.5l-1.75 4M7.5 14l-1 4.25M14 14l1 4.25M2.5 17c4.5 4 12.5 4.25 18-.25M6 11.25l-3 2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yq5wl7b0u {
  d: path("M5.5 9.5H16V14H5.5Z");
}

</style>
