<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="nzt1986ry"/><path class="zmyxryokd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:influencer-star-sharp" /></template>
<style>
.nzt1986ry {
  cx: 9.5px;
  cy: 8.5px;
  r: 3.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zmyxryokd {
  d: path("M4 20.25h11.75v-.75c0-3-2.8-5.25-6.25-5.25S3.25 16.5 3.25 19.5v.75zM18.14 3.07l.69 1.53l.14.32l.35.03l1.66.18l.35.04l-.26.23l-1.24 1.13l-.26.23l.07.34l.35 1.64l.07.34l-.31-.17l-1.45-.84l-.3-.17l-.3.17l-1.45.84l-.31.17l.07-.34l.35-1.64l.07-.34l-.26-.23l-1.24-1.13l-.26-.23l.35-.04l1.66-.18l.35-.03l.14-.32l.69-1.53l.14-.32z");
}

</style>
