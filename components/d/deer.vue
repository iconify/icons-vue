<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="p_ipandas"/><path class="bk1xebb-s"/><path class="bz7b-0rtu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:deer" /></template>
<style>
.bk1xebb-s {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 10.25C9 7.5 7.25 5.5 5 4.5m2.25 1.25l.25-3m6.75 7.5C15 7.5 16.75 5.5 19 4.5m-2.25 1.25l-.25-3");
}

.bz7b-0rtu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.5 13h.01m2.99 0h.01");
}

.p_ipandas {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 10.25h8c0 3.25-.9 6.75-2.15 9.6a2 2 0 0 1-3.7 0C8.9 17 8 13.5 8 10.25m0 1c-1.9.6-3.6.2-4.75-1.25C4.75 9 6.5 8.75 8 9.5Zm8 0c1.9.6 3.6.2 4.75-1.25c-1.5-1-3.25-1.25-4.75-.5Z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
