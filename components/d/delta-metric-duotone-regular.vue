<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mdyd30bgr"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="i92yi0bmq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:delta-metric-duotone-regular" /></template>
<style>
.i92yi0bmq {
  d: path("m8 16 4 -4 4 4Z");
}

.mdyd30bgr {
  fill: currentColor;
  d: path("m8 16 4 -4 4 4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.r3faxubne {
  d: path("M4 4v16");
}

</style>
