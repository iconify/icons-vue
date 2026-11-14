<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zgatq7pvz"/><path class="vtpgnebtv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:debrief-meeting" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vtpgnebtv {
  d: path("M8.5 8V5a2 2 0 0 1 2-2h9a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2v2.5L17 13h-1.5M6 13l2 2l4-4");
}

.zgatq7pvz {
  d: path("M4.5 8h9a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2h-5l-4 3v-3a2 2 0 0 1-2-2v-6a2 2 0 0 1 2-2Z");
}

</style>
