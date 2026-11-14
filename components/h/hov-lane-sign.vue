<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dh2jzoboc"/><path class="qcbxp-bfq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hov-lane-sign" /></template>
<style>
.dh2jzoboc {
  d: path("m12 2l10 10l-10 10L2 12Z");
}

.qcbxp-bfq {
  d: path("M7.5 13.5V12l2.25-3h4.5l2.25 3v1.5h-1a1.5 1.5 0 0 0-3 0h-1a1.5 1.5 0 0 0-3 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
