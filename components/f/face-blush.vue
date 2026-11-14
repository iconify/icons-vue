<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v1rk63baw"/><path class="w28ce8bfd"/><path class="tteepehna"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:face-blush" /></template>
<style>
.tteepehna {
  fill: currentColor;
  d: path("M5.25 13a1.5 1 0 1 0 3 0a1.5 1 0 1 0-3 0Zm10.5 0a1.5 1 0 1 0 3 0a1.5 1 0 1 0-3 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v1rk63baw {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0Zm6-2.75h.01m6.99 0h.01");
}

.w28ce8bfd {
  d: path("M9.75 16q2.25 2.75 4.5 0");
}

</style>
