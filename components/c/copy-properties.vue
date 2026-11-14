<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qpofv-b0o"/><path class="ob_ul2boi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:copy-properties" /></template>
<style>
.ob_ul2boi {
  d: path("M8.5 2.5h7v3h-7ZM12 10l3.5 3.5L12 17l-3.5-3.5Z");
}

.qpofv-b0o {
  d: path("M4.5 4h15v17.5h-15Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
