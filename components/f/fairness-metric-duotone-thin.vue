<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gms_xv68n"/><path class="yu-j7jb_g"/><path class="za9t2xbik"/><path class="rhsyuac4f"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="ndyoa79lx"/><path class="w706_-bdv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:fairness-metric-duotone-thin" /></template>
<style>
.gms_xv68n {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ndyoa79lx {
  d: path("M9 10v8");
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.r3faxubne {
  d: path("M4 4v16");
}

.rhsyuac4f {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 10v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w706_-bdv {
  d: path("M15 10v8");
}

.yu-j7jb_g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.za9t2xbik {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 10v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
