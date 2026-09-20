<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yi2tajbnx"/><path class="qey1ipjhc"/><path class="qfaxfv35t"/><path class="mbt4yzbhr"/><path class="i67oc1bla"/><path class="nzhcuvf_z"/><path class="mkk0o-9le"/><path class="z9ittvbis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:aurora-duotone-regular" /></template>
<style>
.i67oc1bla {
  d: path("M5 16V8l4 -4");
}

.mbt4yzbhr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mkk0o-9le {
  d: path("M15 16V8l4 -4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nzhcuvf_z {
  d: path("M10 16V8l4 -4");
}

.qey1ipjhc {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 16V8l4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qfaxfv35t {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 16V8l4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yi2tajbnx {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 16V8l4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z9ittvbis {
  d: path("M2 19h20");
}

</style>
