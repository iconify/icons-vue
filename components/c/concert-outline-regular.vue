<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u8q22mbqe"/><path class="iyj_k-bwo"/><path class="xo7ududad"/><path class="nb8rxih9e"/><path class="tuc-wpbfs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:concert-outline-regular" /></template>
<style>
.iyj_k-bwo {
  d: path("M12 11v4");
}

.nb8rxih9e {
  d: path("M9 21a3 3 0 0 1 6 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tuc-wpbfs {
  d: path("M15 21a3 3 0 0 1 6 0");
}

.u8q22mbqe {
  d: path("M9 5a3 3 0 0 1 3 -3 3 3 0 0 1 3 3v3a3 3 0 0 1 -3 3 3 3 0 0 1 -3 -3Z");
}

.xo7ududad {
  d: path("M3 21a3 3 0 0 1 6 0");
}

</style>
