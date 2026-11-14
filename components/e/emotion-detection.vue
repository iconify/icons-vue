<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="chyc-l6dq"/><path class="kjo872m0e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:emotion-detection" /></template>
<style>
.chyc-l6dq {
  d: path("M3 8V5.5A2.5 2.5 0 0 1 5.5 3H8m8 0h2.5A2.5 2.5 0 0 1 21 5.5V8m0 8v2.5a2.5 2.5 0 0 1-2.5 2.5H16m-8 0H5.5A2.5 2.5 0 0 1 3 18.5V16m3-4a6 6 0 1 0 12 0a6 6 0 1 0-12 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kjo872m0e {
  d: path("M14.382 13.875a2.75 2.75 0 0 1-4.764 0M10 10h.01M14 10h.01");
}

</style>
