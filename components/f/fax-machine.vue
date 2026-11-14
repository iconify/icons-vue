<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2dek9x1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fax-machine" /></template>
<style>
.f2dek9x1n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9.5h19V21h-19Zm4 0V4a1 1 0 0 1 1-1h8l2 2v4.5M6 13v4.5m7-4h.01m3.49 0h.01M13 17h.01m3.49 0h.01");
}

</style>
