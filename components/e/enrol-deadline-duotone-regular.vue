<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sv5la6biz"/><path class="ixbhvpb_u"/><path class="cu26jmb_i"/><path class="j835zw5-z"/><path class="yc_i1qanr"/><path class="ldha4ac1c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:enrol-deadline-duotone-regular" /></template>
<style>
.cu26jmb_i {
  d: path("M3 7a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.ixbhvpb_u {
  fill: currentColor;
  d: path("M10 15a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.j835zw5-z {
  d: path("M3 9h18");
}

.ldha4ac1c {
  d: path("M13 12v3h3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sv5la6biz {
  fill: currentColor;
  d: path("M3 7a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.yc_i1qanr {
  d: path("M10 15a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
