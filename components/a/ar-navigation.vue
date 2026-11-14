<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h8xrxkbnm"/><path class="iggzz_quh"/><path class="ol-k0xutu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ar-navigation" /></template>
<style>
.h8xrxkbnm {
  d: path("M7.5 4.5h9l5 15.5h-19Z");
}

.iggzz_quh {
  d: path("M10.5 17v-5a2 2 0 0 1 2-2H15");
}

.ol-k0xutu {
  d: path("m13 8l2 2l-2 2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
