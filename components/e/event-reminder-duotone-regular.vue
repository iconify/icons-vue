<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j2zgmcqps"/><path class="bcd4ip6hz"/><path class="ewxguxn4h"/><path class="ipv0cebdm"/><path class="q3dplub_k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:event-reminder-duotone-regular" /></template>
<style>
.bcd4ip6hz {
  fill: currentColor;
  d: path("M13 16a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ewxguxn4h {
  d: path("M2 6h11v3l-2 2 2 2v3H2v-3l2 -2 -2 -2Z");
}

.ipv0cebdm {
  d: path("M13 16a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.j2zgmcqps {
  fill: currentColor;
  d: path("M2 6h11v3l-2 2 2 2v3H2v-3l2 -2 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q3dplub_k {
  d: path("M17 16v-3");
}

</style>
