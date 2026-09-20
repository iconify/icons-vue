<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ekb2lnbaz"/><path class="j_4k-bcfw"/><path class="gcalxb98a"/><path class="hclo6jb2r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:carbon-monoxide-alarm-duotone-regular" /></template>
<style>
.ekb2lnbaz {
  fill: currentColor;
  d: path("M4 10a8 8 0 0 1 16 0v8a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.gcalxb98a {
  d: path("M8 13h8");
}

.hclo6jb2r {
  d: path("M8 16h8");
}

.j_4k-bcfw {
  d: path("M4 10a8 8 0 0 1 16 0v8a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
