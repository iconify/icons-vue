<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="m57dflblt"/><path class="q-qqnwbyu"/><path class="ku9kybbms"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:goat-farm" /></template>
<style>
.ku9kybbms {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 21.25h18.5");
}

.m57dflblt {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 10.25h6.75q1 0 1.33-.94l1.09-3.12q.33-.94 1.3-1.18l.06-.02q.97-.24 1.65.49l1.89 2.04q.68.73.18 1.36q-.5.62-1.48.44l-.79-.14q-.98-.18-1.16.8l-.64 3.54q-.18.98-1.18.98H6q-1 0-1-1v-2.25q0-1 1-1m.5 4.25v3.75M9 14.5v3.75m3.5-3.75v3.75m2.25-3.75v3.75M16.25 5Q15.875 3.5 14 2.75m6 6.75l-.5 1.75M5 10.5l-1.25-2");
}

.q-qqnwbyu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.75 6.75h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
