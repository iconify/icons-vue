<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c7pp32b9e"/><path class="dm3fa1b9h"/><path class="tms3uhrdp"/><path class="qm0cn0b3x"/><path class="x26a8iq1c"/><path class="ugztwkaee"/><path class="j-bg0m85s"/><path class="th8j40bfn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:event-bus-duotone-regular" /></template>
<style>
.c7pp32b9e {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 12h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dm3fa1b9h {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 5v4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j-bg0m85s {
  d: path("M12 14.5V19");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qm0cn0b3x {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 5v4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.th8j40bfn {
  d: path("M18 5v4.5");
}

.tms3uhrdp {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 14.5V19");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ugztwkaee {
  d: path("M6 5v4.5");
}

.x26a8iq1c {
  d: path("M2 12h20");
}

</style>
