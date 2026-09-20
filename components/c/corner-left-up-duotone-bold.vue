<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="t4n3h8lcd"/><path class="b1z-4kbes"/><path class="mwaecstwf"/><path class="p1z08ccdv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:corner-left-up-duotone-bold" /></template>
<style>
.b1z-4kbes {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m5 9 5 -5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mwaecstwf {
  d: path("M20 20H10V4");
}

.p1z08ccdv {
  d: path("m5 9 5 -5 5 5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t4n3h8lcd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20 20H10V4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
