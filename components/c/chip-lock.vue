<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bppnlvb5e"/><path class="f_vi4yefw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chip-lock" /></template>
<style>
.bppnlvb5e {
  d: path("M6.5 3.5h11v17h-11Z");
}

.f_vi4yefw {
  d: path("M14 3.5a2 2 0 0 1-4 0M2.5 8h4m-4 4h4m-4 4h4m11-8h4m-4 4h4m-4 4h4M9.75 12h4.5v3.5h-4.5Zm1 0v-1a1.25 1.25 0 0 1 2.5 0v1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
