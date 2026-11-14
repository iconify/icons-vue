<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zf5rq9bri"/><path class="gjch21gtt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hvac-unit" /></template>
<style>
.gjch21gtt {
  d: path("M6 12a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm11-3h4.5M17 14h4.5M10 12h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zf5rq9bri {
  d: path("M3 4h14v16H3Z");
}

</style>
