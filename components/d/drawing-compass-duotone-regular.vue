<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dx3zvablc"/><path class="tja2w6qai"/><path class="uje4ubcmp"/><path class="wnbj5_30e"/><path class="fnf6pdbdu"/><path class="xwissob6k"/><path class="d4f9j2bku"/><path class="x1_r36phd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:drawing-compass-duotone-regular" /></template>
<style>
.d4f9j2bku {
  d: path("m12 9 6 6v4");
}

.dx3zvablc {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 3v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fnf6pdbdu {
  d: path("M12 3v6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tja2w6qai {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m12 9 -6 6v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uje4ubcmp {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m12 9 6 6v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wnbj5_30e {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x1_r36phd {
  d: path("M9 12h6");
}

.xwissob6k {
  d: path("m12 9 -6 6v4");
}

</style>
