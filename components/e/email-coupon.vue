<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jg087qttg"/><path class="heagg9bky"/><path class="l9j0qbc6t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:email-coupon" /></template>
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

.jg087qttg {
  d: path("M2.5 11v8a2 2 0 0 0 2 2h15a2 2 0 0 0 2-2v-8");
}

.l9j0qbc6t {
  d: path("M6.5 13.5v-4a1.5 1.5 0 0 0 0-3V3h11v3.5a1.5 1.5 0 0 0 0 3v4M10 11l4-4.5m-4 0h.01M14 11h.01");
}

</style>
