<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gkuzynynh"/><path class="i12f54b4f"/><path class="okr3mhbrq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:attar-bottle" /></template>
<style>
.gkuzynynh {
  d: path("M6 15.5a6 6 0 1 0 12 0a6 6 0 1 0-12 0Z");
}

.i12f54b4f {
  d: path("M10.25 9.75V7h3.5v2.75");
}

.okr3mhbrq {
  d: path("M9.75 4.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
