<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u79uzdb3f"/><path class="mobnzkbbn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:grid-battery" /></template>
<style>
.mobnzkbbn {
  d: path("m16.25 8l-2 4h3l-2 4");
}

.u79uzdb3f {
  d: path("M2.5 6h19v12h-19Zm4 3v6M10 9v6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
