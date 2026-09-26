<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="juia08uox"/><path class="u9-e2p27r"/><path class="f4vx4ccga"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:calendar-off-sharp-duotone" /></template>
<style>
.f4vx4ccga {
  d: path("M1.70715 1.70703L22.293 22.2928");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.juia08uox {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 4L10 10H6V12H11V11L22 22H3C2.4477 22 2 21.5523 2 21V5C2 4.4477 2.4477 4 3 4H4Z");
  stroke: none;
}

.u9-e2p27r {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 4C21.5523 4 22 4.4477 22 5V18.3428L7.65723 4H21Z");
  stroke: none;
}

</style>
