<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fcxupekig"/><path class="mhfrl8bav"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bin-hazardous" /></template>
<style>
.fcxupekig {
  d: path("M2.5 6h15M8 6V4h4v2M4 6l1.5 13h9l.747-6.471m.068-.596L16 6");
}

.mhfrl8bav {
  d: path("M5.5 19.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm12.5-5v3.5M18 21h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
