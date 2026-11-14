<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jsatwlp0c"/><path class="r0u_sr26s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:altar-table" /></template>
<style>
.jsatwlp0c {
  d: path("M3 21.5V12h18v9.5");
}

.r0u_sr26s {
  d: path("m3 16.5l9 2.5l9-2.5m-11-11h4V12h-4ZM12 3h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
