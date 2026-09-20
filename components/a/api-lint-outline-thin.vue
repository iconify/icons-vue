<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p367mshbv"/><path class="rseiusb3q"/><path class="rxfxjn7zd"/><path class="pa2oc9mpz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:api-lint-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p367mshbv {
  d: path("M5.5 10a6.5 6.5 0 1 0 13 0 6.5 6.5 0 1 0 -13 0");
}

.pa2oc9mpz {
  d: path("M9.5 11h5");
}

.rseiusb3q {
  d: path("M16.5 14.5 21 19");
}

.rxfxjn7zd {
  d: path("M9.5 8h5");
}

</style>
