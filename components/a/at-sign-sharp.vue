<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="m10ymsugb"/><path class="p9cw2vbot"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:at-sign-sharp" /></template>
<style>
.m10ymsugb {
  cx: 12px;
  cy: 12px;
  r: 3.5px;
}

.p9cw2vbot {
  d: path("M15.5 8.5v4.75a2.5 2.5 0 0 0 5 0V12a8.5 8.5 0 1 0-3.75 7.05");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
