<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gzraq3bes"/><path class="kh45z_ozd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fire-alarm-sounding" /></template>
<style>
.gzraq3bes {
  d: path("M2.5 6h12v12h-12Z");
}

.kh45z_ozd {
  d: path("M5.25 14.75h6.5m-5.5 0V12a2.25 2.25 0 0 1 4.5 0v2.75m6.663-5.875a6.25 6.25 0 0 1 0 6.25m2.598-7.75a9.25 9.25 0 0 1 0 9.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
