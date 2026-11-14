<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vz-ox2xnn"/><path class="icmo0obod"/><path class="p016wcc4d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hair-wax-tin" /></template>
<style>
.icmo0obod {
  d: path("M4 8.25v8.25a8 2.75 0 0 0 16 0V8.25");
}

.p016wcc4d {
  d: path("M4 12.5a8 2.75 0 0 0 16 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vz-ox2xnn {
  d: path("M3 7a9 2.5 0 1 0 18 0A9 2.5 0 1 0 3 7Z");
}

</style>
