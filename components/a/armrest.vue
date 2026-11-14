<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pt_--cc_a"/><path class="kn4_f8ovk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:armrest" /></template>
<style>
.kn4_f8ovk {
  d: path("M5.5 9H13v3H5.5Z");
}

.pt_--cc_a {
  d: path("M14.5 2.5H18A1.5 1.5 0 0 1 19.5 4l-1 15a1.5 1.5 0 0 1-1.5 1.5H5A1.5 1.5 0 0 1 3.5 19v-2.5A1.5 1.5 0 0 1 5 15h8V4a1.5 1.5 0 0 1 1.5-1.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
