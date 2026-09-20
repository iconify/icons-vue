<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t5v_djbzx"/><path class="j2xefnnxl"/><path class="jq9hovbrs"/><path class="yomctlb4k"/><path class="r1ix196dy"/><path class="lit20acsf"/><path class="u41hfsjfh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:audio-timestamp-duotone-regular" /></template>
<style>
.j2xefnnxl {
  fill: currentColor;
  d: path("M9 10.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.jq9hovbrs {
  d: path("M14 4h5a3 3 0 0 1 3 3v7a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V7a3 3 0 0 1 3 -3h5");
}

.lit20acsf {
  d: path("M12 7.5v3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r1ix196dy {
  d: path("M9 10.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.t5v_djbzx {
  fill: currentColor;
  d: path("M14 4h5a3 3 0 0 1 3 3v7a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V7a3 3 0 0 1 3 -3h5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.u41hfsjfh {
  d: path("M12 10.5h2.5");
}

.yomctlb4k {
  d: path("M7 17v4l4 -4");
}

</style>
