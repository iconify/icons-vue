<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="inzw2gkjz"/><path class="ld04aiich"/><path class="lmnp7qbpj"/><path class="ooyv_6epc"/><path class="jfhg8zbol"/><path class="jlojnsdlu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:free-wifi-duotone-regular" /></template>
<style>
.inzw2gkjz {
  fill: currentColor;
  d: path("M11 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.jfhg8zbol {
  d: path("M3.54 13.92a9 9 0 0 1 16.92 0");
}

.jlojnsdlu {
  d: path("M11 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.ld04aiich {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7.77 15.46a4.5 4.5 0 0 1 8.46 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lmnp7qbpj {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3.54 13.92a9 9 0 0 1 16.92 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ooyv_6epc {
  d: path("M7.77 15.46a4.5 4.5 0 0 1 8.46 0");
}

</style>
