<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b3muyfg1w"/><path class="te1zb6b_s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:leaf-hole" /></template>
<style>
.b3muyfg1w {
  d: path("M5.25 18.75c0-9.5 5.5-15 15-15c0 9.5-5.5 15-15 15Zm-1.5 1.5l1.5-1.5");
}

.te1zb6b_s {
  d: path("M10.5 11.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
