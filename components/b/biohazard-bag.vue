<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mgpldu_ny"/><path class="h8-4eb2cp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:biohazard-bag" /></template>
<style>
.h8-4eb2cp {
  d: path("M14 9.5a2.5 2.5 0 1 1-4 0a2 2 0 0 0 4 0Zm1.5 9.5a2.5 2.5 0 1 1 2-3.25a2 2 0 0 0-2 3.25Zm-9-3.25a2.5 2.5 0 1 1 2 3.25a2 2 0 0 0-2-3.25Z");
}

.mgpldu_ny {
  d: path("M8.5 7c-3 2.5-4 6-3.5 9.5c.5 3.25 3.25 5 7 5s6.5-1.75 7-5c.5-3.5-.5-7-3.5-9.5Zm1 0l-1-4.5l3.5 2l3.5-2l-1 4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
