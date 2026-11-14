<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eoz3zibrm"/><path class="gghcu9x9r"/><path class="uzx24gbgo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fingerprint-scanner-police" /></template>
<style>
.eoz3zibrm {
  d: path("M4.5 2.5h15v19h-15Z");
}

.gghcu9x9r {
  d: path("M8 14.5v-4a4 4 0 0 1 8 0v4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uzx24gbgo {
  d: path("M10.75 14.5v-4a1.25 1.25 0 0 1 2.5 0v4M9 18h6");
}

</style>
