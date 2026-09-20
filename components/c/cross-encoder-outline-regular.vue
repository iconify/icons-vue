<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gig9ivbwc"/><path class="kfs1394gk"/><path class="z5135gcut"/><path class="ba_a_obvy"/><path class="rzfubwb2e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cross-encoder-outline-regular" /></template>
<style>
.ba_a_obvy {
  d: path("m8 16 4 -4");
}

.gig9ivbwc {
  d: path("M2 8h6");
}

.kfs1394gk {
  d: path("M2 16h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rzfubwb2e {
  d: path("M12 12h10");
}

.z5135gcut {
  d: path("m8 8 4 4");
}

</style>
