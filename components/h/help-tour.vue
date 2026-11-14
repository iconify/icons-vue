<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qflg01q3e"/><path class="d-hgvwols"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:help-tour" /></template>
<style>
.d-hgvwols {
  d: path("M5.5 8.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm10 3a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-7-3c4 0 3 3 7 3");
}

.qflg01q3e {
  d: path("M2.5 3.5h19v13h-19Zm9.5 13v4m-3.5 0h7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
