<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mxu4iwysg"/><path class="nii_ngb3a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gantt-baseline" /></template>
<style>
.mxu4iwysg {
  d: path("M3.5 3v18m3-16H17v5H6.5Z");
}

.nii_ngb3a {
  fill: currentColor;
  d: path("M10.5 13.5H21v5H10.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
