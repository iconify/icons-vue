<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ahp9s2bzp"/><path class="qyottkbqu"/><path class="k6x6uv-ap"/><path class="h2va4xb2x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hair-outline-regular" /></template>
<style>
.ahp9s2bzp {
  d: path("M3 6h18v5H3Z");
}

.h2va4xb2x {
  d: path("M17 11v8");
}

.k6x6uv-ap {
  d: path("M12 11v8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qyottkbqu {
  d: path("M7 11v8");
}

</style>
