<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="y1z1czbul"/><path class="iymet_cml"/><path class="jm6ti-b3r"/><path class="d-roobcrg"/><path class="lz2aypuyn"/><path class="r90hdxs8e"/><path class="ic2vvsb1f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:attack-surface-duotone-bold" /></template>
<style>
.d-roobcrg {
  d: path("M8 7v4");
}

.ic2vvsb1f {
  d: path("M13.5 8.5 16 11l2.5 -2.5");
}

.iymet_cml {
  d: path("M15.5 4H19a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V8l4 -4h3.5");
}

.jm6ti-b3r {
  d: path("M6 15h12");
}

.lz2aypuyn {
  d: path("M5.5 8.5 8 11l2.5 -2.5");
}

.r90hdxs8e {
  d: path("M16 7v4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.y1z1czbul {
  fill: currentColor;
  d: path("M15.5 4H19a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V8l4 -4h3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
