<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eukn0bb1j"/><path class="mgaep1b3k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gitops" /></template>
<style>
.eukn0bb1j {
  d: path("M4.25 5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm10 1a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Z");
}

.mgaep1b3k {
  d: path("M6.5 7.25V20.5m10-12.25c0 4.25-10 3.25-10 7.25m8.25 2.5a3.25 3.25 0 0 1 6-1.5m0-2.25v2.25H18.5m2.75 1.5a3.25 3.25 0 0 1-6 1.5m0 2.25V19.5h2.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
