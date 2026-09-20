<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nww9z02wt"/><path class="rh6cspb3h"/><path class="l2k0-c9-j"/><path class="xj_kqitvx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:juice-duotone-bold" /></template>
<style>
.l2k0-c9-j {
  d: path("m6 8 5 -5 5 5");
}

.nww9z02wt {
  fill: currentColor;
  d: path("M6 8v13h10V8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rh6cspb3h {
  d: path("M6 8v13h10V8Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xj_kqitvx {
  d: path("m13 8 5 -5");
}

</style>
