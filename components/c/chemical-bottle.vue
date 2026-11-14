<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c0v_jx-1v"/><path class="ndf_6qdcr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chemical-bottle" /></template>
<style>
.c0v_jx-1v {
  d: path("M10 6.5V8l-4.5 3v8.5a2 2 0 0 0 2 2h9a2 2 0 0 0 2-2V11L14 8V6.5m-5-4h6v4H9Z");
}

.ndf_6qdcr {
  d: path("M8.5 13.5h7v5h-7Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
