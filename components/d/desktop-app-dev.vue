<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m1-mco9vz"/><path class="f4nr3rwjd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:desktop-app-dev" /></template>
<style>
.f4nr3rwjd {
  d: path("M6 6h12v7.5H6Zm0 2.75h12");
}

.m1-mco9vz {
  d: path("M2.5 3h19v13.5h-19ZM12 16.5v4m-4 0h8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
