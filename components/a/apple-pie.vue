<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d-ca_bb8s"/><path class="zfm18kbce"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:apple-pie" /></template>
<style>
.d-ca_bb8s {
  d: path("M10.5 13.5H18a2.5 2.5 0 0 1-1 3.75A2.5 2.5 0 0 1 14.25 20a2.5 2.5 0 0 1-3.75 1a2.5 2.5 0 0 1-3.75-1A2.5 2.5 0 0 1 4 17.25a2.5 2.5 0 0 1-1-3.75a2.5 2.5 0 0 1 1-3.75A2.5 2.5 0 0 1 6.75 7a2.5 2.5 0 0 1 3.75-1Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zfm18kbce {
  d: path("M13.5 10.5H21a2.5 2.5 0 0 0-1-3.75A2.5 2.5 0 0 0 17.25 4a2.5 2.5 0 0 0-3.75-1Z");
}

</style>
