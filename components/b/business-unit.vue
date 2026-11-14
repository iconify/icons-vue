<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="je520hb2t"/><path class="kq4taj50n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:business-unit" /></template>
<style>
.je520hb2t {
  d: path("M10.75 13.25v-8a8 8 0 1 0 8 8Z");
}

.kq4taj50n {
  d: path("M13.5 10.5v-8a8 8 0 0 1 8 8Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
