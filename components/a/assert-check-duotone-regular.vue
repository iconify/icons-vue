<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pfkkes-5w"/><path class="e5omm4bvi"/><path class="j7c1ctjlf"/><path class="pev_t0bpq"/><path class="vdp61xcuu"/><path class="ik6cgdc2x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:assert-check-duotone-regular" /></template>
<style>
.e5omm4bvi {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16.5 4H19v16h-2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ik6cgdc2x {
  d: path("m8.5 12 2.5 2.5 5 -5");
}

.j7c1ctjlf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m8.5 12 2.5 2.5 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pev_t0bpq {
  d: path("M7.5 4H5v16h2.5");
}

.pfkkes-5w {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7.5 4H5v16h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vdp61xcuu {
  d: path("M16.5 4H19v16h-2.5");
}

</style>
