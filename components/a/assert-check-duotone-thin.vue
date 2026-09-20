<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g_wi1xipb"/><path class="nw4500bkf"/><path class="dldrzbcrl"/><path class="pev_t0bpq"/><path class="vdp61xcuu"/><path class="ik6cgdc2x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:assert-check-duotone-thin" /></template>
<style>
.dldrzbcrl {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m8.5 12 2.5 2.5 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g_wi1xipb {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7.5 4H5v16h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ik6cgdc2x {
  d: path("m8.5 12 2.5 2.5 5 -5");
}

.nw4500bkf {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16.5 4H19v16h-2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pev_t0bpq {
  d: path("M7.5 4H5v16h2.5");
}

.vdp61xcuu {
  d: path("M16.5 4H19v16h-2.5");
}

</style>
