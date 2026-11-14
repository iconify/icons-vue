<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yy7wvbbcq"/><path class="ocai_rdcd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cue-ball" /></template>
<style>
.ocai_rdcd {
  d: path("M15 8a4 4 0 0 1 4 4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yy7wvbbcq {
  d: path("M8.5 12a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0Zm-6 0h6");
}

</style>
