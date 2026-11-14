<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eoz3zibrm"/><path class="rrxiuy_pd"/><path class="db0hvl-ej"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:care-plan-document" /></template>
<style>
.db0hvl-ej {
  d: path("M8.5 8.75c0 3.75 7 .75 7 4.5m-2.75 3L14.5 18l2.5-2.75");
}

.eoz3zibrm {
  d: path("M4.5 2.5h15v19h-15Z");
}

.rrxiuy_pd {
  fill: currentColor;
  d: path("M7.25 6.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
