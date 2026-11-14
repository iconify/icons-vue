<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f54ejxb7b"/><path class="bv755zb2e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:call-transfer-warm" /></template>
<style>
.bv755zb2e {
  d: path("M16.25 5.75L18.5 8l2.25-2.25");
}

.f54ejxb7b {
  d: path("M3 13.5A1.5 1.5 0 0 1 4.5 12H6l1 2.5l-1.5 1.25a7 7 0 0 0 2.75 2.75L9.5 17l2.5 1v1.5a1.5 1.5 0 0 1-1.5 1.5A8 8 0 0 1 3 13.5m13.25 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-1.75 8c0-2 1.75-3.25 3.75-3.25S22 19.5 22 21.5M6.5 8a6 6 0 0 1 12 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
