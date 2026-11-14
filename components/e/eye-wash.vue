<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tii8-1brb"/><path class="yohi0x--v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:eye-wash" /></template>
<style>
.tii8-1brb {
  d: path("M3.5 9c3-4.75 14-4.75 17 0c-3 4.75-14 4.75-17 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yohi0x--v {
  d: path("M10 9a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-2.5 6s-1.75 2.25-1.75 3.75a1.75 1.75 0 0 0 3.5 0C9.25 17.25 7.5 15 7.5 15Zm9 0s-1.75 2.25-1.75 3.75a1.75 1.75 0 0 0 3.5 0c0-1.5-1.75-3.75-1.75-3.75Z");
}

</style>
