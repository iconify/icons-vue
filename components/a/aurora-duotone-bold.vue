<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="v0pkd3-mo"/><path class="npmftn1br"/><path class="shgc0_b_y"/><path class="d5b4fcc2f"/><path class="i67oc1bla"/><path class="nzhcuvf_z"/><path class="mkk0o-9le"/><path class="z9ittvbis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:aurora-duotone-bold" /></template>
<style>
.d5b4fcc2f {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.i67oc1bla {
  d: path("M5 16V8l4 -4");
}

.mkk0o-9le {
  d: path("M15 16V8l4 -4");
}

.npmftn1br {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 16V8l4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nzhcuvf_z {
  d: path("M10 16V8l4 -4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.shgc0_b_y {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 16V8l4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v0pkd3-mo {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 16V8l4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z9ittvbis {
  d: path("M2 19h20");
}

</style>
