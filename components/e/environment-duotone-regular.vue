<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mhel7mbpa"/><path class="azyfb8wgh"/><path class="fmlaifbpn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:environment-duotone-regular" /></template>
<style>
.azyfb8wgh {
  d: path("m4 12 8 -8 8 8v8H4Z");
}

.fmlaifbpn {
  d: path("M12 16v4");
}

.mhel7mbpa {
  fill: currentColor;
  d: path("m4 12 8 -8 8 8v8H4Z");
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

</style>
