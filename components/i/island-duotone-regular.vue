<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jry43pbmm"/><path class="dk2_9r6pl"/><path class="bazy0m0ne"/><path class="z_4qj1bfx"/><path class="ox3evc4xr"/><path class="azjtlhb3x"/><path class="o8od38cnm"/><path class="hiqcqfbaf"/><path class="rqk3146zh"/><path class="uysczfb3e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:island-duotone-regular" /></template>
<style>
.azjtlhb3x {
  d: path("M4 18a8 8 0 0 1 16 0");
}

.bazy0m0ne {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 8v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dk2_9r6pl {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 18h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hiqcqfbaf {
  d: path("M12 8v10");
}

.jry43pbmm {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 18a8 8 0 0 1 16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o8od38cnm {
  d: path("M4 18h16");
}

.ox3evc4xr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 11a3 3 0 0 1 0 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rqk3146zh {
  d: path("M9 5a3 3 0 0 1 0 6");
}

.uysczfb3e {
  d: path("M15 11a3 3 0 0 1 0 -6");
}

.z_4qj1bfx {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 5a3 3 0 0 1 0 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
