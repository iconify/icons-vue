<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qfw01abnj"/><path class="mo4l_ssux"/><path class="mj44qtbic"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:face-cap" /></template>
<style>
.mj44qtbic {
  d: path("M4.5 12a7.5 7.5 0 0 0 15 0M9.25 15h.01m5.49 0h.01");
}

.mo4l_ssux {
  d: path("M4.5 12q7.5-2.5 17 .5");
}

.qfw01abnj {
  d: path("M4.5 12C4.5 6.5 8 4 12 4s7.5 2.5 7.5 8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
