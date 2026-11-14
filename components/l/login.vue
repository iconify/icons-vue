<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dnl-t-b2k"/><path class="m-k1_cjpf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:login" /></template>
<style>
.dnl-t-b2k {
  d: path("M11 6V4.5a2 2 0 0 1 2-2h5.5a2 2 0 0 1 2 2v15a2 2 0 0 1-2 2H13a2 2 0 0 1-2-2V18m-8-6h13");
}

.m-k1_cjpf {
  d: path("M12.5 8.5L16 12l-3.5 3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
