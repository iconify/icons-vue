<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hcobkotyf"/><path class="vjsb4tb9h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gps-track" /></template>
<style>
.hcobkotyf {
  d: path("M16.5 15s-4-4.25-4-7.5a4 4 0 0 1 8 0c0 3.25-4 7.5-4 7.5Zm-13 2h.01m2.99 3.5h.01m3.99-1h.01M13.5 17h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vjsb4tb9h {
  d: path("M15 7.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

</style>
