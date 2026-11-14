<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wax_pvl1y"/><path class="z0jkpv9gj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cable-manhole" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wax_pvl1y {
  d: path("M7.5 12a7 7 0 1 0 14 0a7 7 0 1 0-14 0Zm-5 5c2.5 0 2.5-5 5-5");
}

.z0jkpv9gj {
  d: path("M10.25 12a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0ZM13 12h3");
}

</style>
