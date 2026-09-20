<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="j-nhdjbnr"/><path class="z0e68ebar"/><path class="pm7w7pbbr"/><path class="pev_t0bpq"/><path class="vdp61xcuu"/><path class="ik6cgdc2x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:assert-check-duotone-bold" /></template>
<style>
.ik6cgdc2x {
  d: path("m8.5 12 2.5 2.5 5 -5");
}

.j-nhdjbnr {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7.5 4H5v16h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pev_t0bpq {
  d: path("M7.5 4H5v16h2.5");
}

.pm7w7pbbr {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m8.5 12 2.5 2.5 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vdp61xcuu {
  d: path("M16.5 4H19v16h-2.5");
}

.z0e68ebar {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16.5 4H19v16h-2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
