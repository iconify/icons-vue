<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h7vr07ufd"/><path class="w5l4p1byx"/><path class="bvjga9f7b"/><path class="k6nj2fbya"/><path class="cbvfl-_0s"/><path class="f0zlw3bmh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:drilldown-duotone-bold" /></template>
<style>
.bvjga9f7b {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 15v4h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cbvfl-_0s {
  d: path("M6 9v4h15");
}

.f0zlw3bmh {
  d: path("M10 15v4h11");
}

.h7vr07ufd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.w5l4p1byx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 9v4h15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
