<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="c6vt1lbds"/><path class="eazee3bcp"/><path class="goa6xmsjx"/><path class="qtnuldbzb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cry" /></template>
<style>
.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.eazee3bcp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.25 7.75l2.5-1m7 1l-2.5-1");
}

.goa6xmsjx {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 10.25h.01m5.99 0h.01");
}

.qtnuldbzb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 17c.7-.85 1.4-1.25 2.25-1.25s1.55.4 2.25 1.25M7 12.75c.65.95 1 1.6 1 2.15a1 1 0 0 1-2 0c0-.55.35-1.2 1-2.15");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
