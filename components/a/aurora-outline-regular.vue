<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i67oc1bla"/><path class="nzhcuvf_z"/><path class="mkk0o-9le"/><path class="z9ittvbis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:aurora-outline-regular" /></template>
<style>
.i67oc1bla {
  d: path("M5 16V8l4 -4");
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

.z9ittvbis {
  d: path("M2 19h20");
}

</style>
