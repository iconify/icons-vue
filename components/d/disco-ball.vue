<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="fgkpf5b9v"/><circle class="sf-oocn4o"/><path class="bbpfwnbwk"/><path class="saibhebxm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:disco-ball" /></template>
<style>
.bbpfwnbwk {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 9.5h.01M8.5 13h.01m6.99 0h.01M12 16.5h.01");
}

.fgkpf5b9v {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75v2");
}

.saibhebxm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M19.5 2.75q.21 1.54 1.75 1.75q-1.54.21-1.75 1.75q-.21-1.54-1.75-1.75q1.54-.21 1.75-1.75");
}

.sf-oocn4o {
  cx: 12px;
  cy: 13px;
  r: 8.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
