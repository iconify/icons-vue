<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="il2e3ku6p"/><path class="gzypk_xwk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:doorbell-camera-motion" /></template>
<style>
.gzypk_xwk {
  d: path("M6 7.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-.25 8a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM16.5 3a9.75 9.75 0 0 1 0 9m3.25-10a13 13 0 0 1 0 11");
}

.il2e3ku6p {
  d: path("M4 2.5h8a1 1 0 0 1 1 1v17a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1v-17a1 1 0 0 1 1-1Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
