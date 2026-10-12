<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="fhvjqwado"/><path class="b0jqmzm3a"/><path class="m7m59qc-v"/><path class="d2_dpab6k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:falling-objects" /></template>
<style>
.b0jqmzm3a {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 9h2v2h-2Z");
}

.d2_dpab6k {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 18a2.5 2.5 0 0 1 5 0");
}

.fhvjqwado {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.98 4.99l7.29 13.02q.98 1.74-1.02 1.74H4.75q-2 0-1.02-1.74l7.29-13.02q.98-1.74 1.96 0");
}

.m7m59qc-v {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 13.75h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
