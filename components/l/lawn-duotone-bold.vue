<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="km2_vvbqp"/><path class="ja18a0bov"/><path class="ad-e62ban"/><path class="yawg8e3_z"/><path class="o8od38cnm"/><path class="tktvzqb2t"/><path class="f__nic5ty"/><path class="mcne0zbsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:lawn-duotone-bold" /></template>
<style>
.ad-e62ban {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 18V6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f__nic5ty {
  d: path("M12 18V6");
}

.ja18a0bov {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 18c0 -4 -1 -7 -2 -11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.km2_vvbqp {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 18h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mcne0zbsf {
  d: path("M17 18c0 -4 1 -7 2 -11");
}

.o8od38cnm {
  d: path("M4 18h16");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tktvzqb2t {
  d: path("M7 18c0 -4 -1 -7 -2 -11");
}

.yawg8e3_z {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 18c0 -4 1 -7 2 -11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
