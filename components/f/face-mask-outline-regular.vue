<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yoftwf7ei"/><path class="gqwusxz8h"/><path class="mbifgmx_w"/><path class="tp86gnbwd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:face-mask-outline-regular" /></template>
<style>
.gqwusxz8h {
  d: path("M3 12h18v3a12 12 0 0 1 -18 0Z");
}

.mbifgmx_w {
  d: path("M3 12V8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tp86gnbwd {
  d: path("M21 12V8");
}

.yoftwf7ei {
  d: path("M6 9a6 6 0 1 0 12 0A6 6 0 1 0 6 9");
}

</style>
