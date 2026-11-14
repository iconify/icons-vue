<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wfazglbfx"/><path class="rkxhx1b5u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:eye-gaze-control" /></template>
<style>
.rkxhx1b5u {
  d: path("M13.283 8.476a3.75 3.75 0 0 1 2.241 2.241m0 2.566a3.75 3.75 0 0 1-2.241 2.241m-2.566 0a3.75 3.75 0 0 1-2.241-2.241m0-2.566a3.75 3.75 0 0 1 2.241-2.241M12 12h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wfazglbfx {
  d: path("M2.5 12C5 7.5 8.25 5.5 12 5.5s7 2 9.5 6.5c-2.5 4.5-5.75 6.5-9.5 6.5s-7-2-9.5-6.5Z");
}

</style>
