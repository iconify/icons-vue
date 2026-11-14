<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z5lz2gbhv"/><path class="ppub1ebcp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:health-student-plan" /></template>
<style>
.ppub1ebcp {
  d: path("M6 11.5V16c0 1.5 2.5 3 6 3s6-1.5 6-3v-4.5M21.5 9v6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z5lz2gbhv {
  d: path("m12 4l9.5 5l-9.5 5l-9.5-5Z");
}

</style>
