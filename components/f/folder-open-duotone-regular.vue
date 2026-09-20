<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lwyrqqb_g"/><path class="m6u_t4bqm"/><path class="y5jslcbiw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:folder-open-duotone-regular" /></template>
<style>
.lwyrqqb_g {
  fill: currentColor;
  d: path("m4 20 8 -8h10l-8 8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.m6u_t4bqm {
  d: path("M4 20V4h5l3 3h7v4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.y5jslcbiw {
  d: path("m4 20 8 -8h10l-8 8Z");
}

</style>
