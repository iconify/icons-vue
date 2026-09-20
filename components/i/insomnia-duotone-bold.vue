<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="d4-4pac7y"/><path class="t5n4yo4aa"/><path class="v105zmblb"/><path class="r3k61hkwm"/><path class="t06rkwfxk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:insomnia-duotone-bold" /></template>
<style>
.d4-4pac7y {
  fill: currentColor;
  d: path("M15 3a9 9 0 1 0 0 18 7 7 0 0 1 0 -18");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.r3k61hkwm {
  d: path("M20 5v7");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t06rkwfxk {
  d: path("M19 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.t5n4yo4aa {
  fill: currentColor;
  d: path("M19 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.v105zmblb {
  d: path("M15 3a9 9 0 1 0 0 18 7 7 0 0 1 0 -18");
}

</style>
