<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wf57v9hap"/><path class="k_a5dlcbg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:handshake" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k_a5dlcbg {
  d: path("m5 14.5l4.75 4.75c.45.45 1.25.45 1.75 0L19 12");
}

.wf57v9hap {
  d: path("m2.5 12l4-4H10l3.5 3.25c.6.55.6 1.45 0 2s-1.5.5-2 0l-1.5-1.5m11.5.25l-4-4h-3l-1.75 1.5");
}

</style>
