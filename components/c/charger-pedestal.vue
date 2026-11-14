<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nl44x236p"/><path class="mepfaph9d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:charger-pedestal" /></template>
<style>
.mepfaph9d {
  d: path("M10.5 6.5L8 11h3l-2.5 4.5");
}

.nl44x236p {
  d: path("M5 2.5h9v19H5ZM14 17c3 0 5-1.5 5-5V7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
