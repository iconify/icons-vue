<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bi1xf-bwn"/><path class="qcda3fbuh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cable-extension" /></template>
<style>
.bi1xf-bwn {
  d: path("M5 2.5v2m3-2v2m-4.5 0h6V7a3 3 0 0 1-6 0Z");
}

.qcda3fbuh {
  d: path("M6.5 10v4a3 3 0 0 0 3 3H12m0-4h9.5v8H12Zm3 4h.01m3.49 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
