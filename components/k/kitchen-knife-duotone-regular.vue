<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qv06t9afb"/><path class="rbdg4rb5l"/><path class="e69i7fcek"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:kitchen-knife-duotone-regular" /></template>
<style>
.e69i7fcek {
  d: path("M17 12h5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qv06t9afb {
  fill: currentColor;
  d: path("M3 17h14V7h-4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rbdg4rb5l {
  d: path("M3 17h14V7h-4Z");
}

</style>
