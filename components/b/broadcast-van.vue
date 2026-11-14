<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d0knv-bpu"/><path class="r7g_rcbva"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:broadcast-van" /></template>
<style>
.d0knv-bpu {
  d: path("M2.5 17.5v-6A1.5 1.5 0 0 1 4 10h10.5l7 4v3.5Z");
}

.r7g_rcbva {
  d: path("M5 19.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM4.5 3.5a3.75 3.75 0 0 0 7.5 0Zm3.75 3.75V10");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
