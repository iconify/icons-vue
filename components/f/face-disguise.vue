<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zdgu3ybil"/><path class="bgr_jwbsl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:face-disguise" /></template>
<style>
.bgr_jwbsl {
  d: path("M10.5 9.5a2.5 2.5 0 1 1-5 0a2.5 2.5 0 1 1 5 0c.5 4.25 2.5 4.25 3 0a2.5 2.5 0 1 1 5 0a2.5 2.5 0 1 1-5 0m-6 8.25q2.25-2.5 4.5-1q2.25-1.5 4.5 1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zdgu3ybil {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0Z");
}

</style>
