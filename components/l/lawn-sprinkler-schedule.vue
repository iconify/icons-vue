<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b8dr2wbmo"/><path class="xhq_ph3sx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lawn-sprinkler-schedule" /></template>
<style>
.b8dr2wbmo {
  d: path("M12.2 13.5H10v-3h4v1.2m-2 1.8v7M6.75 9a6 6 0 0 1 10.5 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xhq_ph3sx {
  d: path("M4.75 6a9.5 9.5 0 0 1 14.5 0M3.5 20.5h8.7m2.8-5h6v5.75h-6Zm0 2.25h6m-4.25-3.25V16m2.5-1.5V16");
}

</style>
