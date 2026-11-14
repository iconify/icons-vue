<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v7101x-uj"/><path class="iou0khb3x"/><path class="oeuqu_z4g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bug-lock" /></template>
<style>
.iou0khb3x {
  d: path("M7.25 8.5a2.5 2.5 0 0 1 4.5 0M2.5 11l3 1m11-1l-3 1m-11 3l3-.5m11 .5l-3-.5M3 19l2.75-1.75M15 17h6v4.5h-6Z");
}

.oeuqu_z4g {
  d: path("M16.25 17v-1.25a1.75 1.75 0 0 1 3.5 0V17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v7101x-uj {
  d: path("M5.5 13.25a4 5.25 0 1 0 8 0a4 5.25 0 1 0-8 0Z");
}

</style>
