<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x9emg4bdv"/><path class="glz1tf0if"/><path clip-rule="evenodd" class="oy3_bdbpk"/><path class="t_z0u4gdv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-bullet-duotone" /></template>
<style>
.glz1tf0if {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 9L16 9C15.4477 9 15 9.4477 15 10L15 14C15 14.5523 15.4477 15 16 15L20 15C21.1046 15 22 14.1046 22 13L22 11C22 9.8954 21.1046 9 20 9Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oy3_bdbpk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 9L8 9C6.8954 9 6 9.8954 6 11L6 13C6 14.1046 6.8954 15 8 15L16 15C16.5523 15 17 14.5523 17 14L17 10C17 9.4477 16.5523 9 16 9Z");
  stroke: none;
}

.t_z0u4gdv {
  d: path("M16 7V17");
}

.x9emg4bdv {
  stroke-opacity: 0.4;
  d: path("M3 3L3 19C3 20.1046 3.8954 21 5 21L21 21");
}

</style>
