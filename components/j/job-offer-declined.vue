<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i45girxkv"/><path class="heagg9bky"/><path class="pldpw4w_c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:job-offer-declined" /></template>
<style>
.heagg9bky {
  d: path("m2.5 11l9.5 6l9.5-6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i45girxkv {
  d: path("M2.5 11v8.5A1.5 1.5 0 0 0 4 21h16a1.5 1.5 0 0 0 1.5-1.5V11");
}

.pldpw4w_c {
  d: path("M5.5 12.75V3.5a1 1 0 0 1 1-1h4.25L9.5 5.25L11 8l-1.5 2.75l.5 5m8.5-3V3.5a1 1 0 0 0-1-1H14l-1.25 2.75L14.25 8l-1.5 2.75l1.25 5");
}

</style>
