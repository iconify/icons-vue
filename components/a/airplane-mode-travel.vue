<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dxsxh5xhc"/><path class="hfnny1jod"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:airplane-mode-travel" /></template>
<style>
.dxsxh5xhc {
  d: path("M6 2.5h12v19H6Z");
}

.hfnny1jod {
  d: path("M12 7v10m-3.5-4l3.5-2l3.5 2m-5.25 4l1.75-.75l1.75.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
