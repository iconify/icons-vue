<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qzj_wwblh"/><path class="d7srefqbi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:descaler" /></template>
<style>
.d7srefqbi {
  d: path("m12 12l3 5.75H9Z");
}

.qzj_wwblh {
  d: path("M9.5 2.5h5v3h-5Zm.5 3v2l-4 3V20a1.5 1.5 0 0 0 1.5 1.5h9A1.5 1.5 0 0 0 18 20v-9.5l-4-3v-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
