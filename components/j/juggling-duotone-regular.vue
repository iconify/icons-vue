<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lzzpbebvm"/><path class="pr270rb6e"/><path class="hf_zxrbcx"/><path class="pgru5cu9h"/><path class="hrm50umfz"/><path class="d_xtg74gy"/><path class="mor-ojbak"/><path class="gcpl_duni"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:juggling-duotone-regular" /></template>
<style>
.d_xtg74gy {
  d: path("M15 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.gcpl_duni {
  d: path("M12 4c6 1 8 7 4 11");
}

.hf_zxrbcx {
  fill: currentColor;
  d: path("M7 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hrm50umfz {
  d: path("M6 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.lzzpbebvm {
  fill: currentColor;
  d: path("M6 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.mor-ojbak {
  d: path("M7 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pgru5cu9h {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 4c6 1 8 7 4 11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pr270rb6e {
  fill: currentColor;
  d: path("M15 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
