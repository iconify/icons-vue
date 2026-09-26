<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tq0g8ab4w"/><path class="wfmckqbpo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:broom-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tq0g8ab4w {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.6106 13.5362C10.257 14.466 6.6399 16.1295 3 15.3456C5.8769 18.8355 12.2148 24.7603 14.5521 20.5399C15.1662 19.4704 16.3379 17.1141 16.1118 16.2453ZM11.6106 13.5362C12.0558 12.2895 13.5424 10.069 15.9271 11.1603C18.0077 12.3742 16.9171 15.0561 16.1118 16.2453Z");
  stroke: none;
}

.wfmckqbpo {
  d: path("M11.6106 13.5362C10.257 14.466 6.6399 16.1295 3 15.3456C5.8769 18.8355 12.2148 24.7603 14.5521 20.5399C15.1662 19.4704 16.3379 17.1141 16.1118 16.2453ZM11.6106 13.5362C12.0558 12.2895 13.5424 10.069 15.9271 11.1603M16.1118 16.2453C16.9171 15.0561 18.0077 12.3742 15.9271 11.1603M15.9271 11.1603L21 2");
}

</style>
