<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v4qx2ccfm"/><path class="sge-6ebfv"/><path class="rr985ibot"/><path class="c3a-odz8a"/><path class="akf7y5bsb"/><path class="xgyiae7-j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:align-center-vertical-duotone-regular" /></template>
<style>
.akf7y5bsb {
  d: path("M8 7h8v4H8Z");
}

.c3a-odz8a {
  d: path("M12 18.5V21");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rr985ibot {
  d: path("M12 3v2.5");
}

.sge-6ebfv {
  fill: currentColor;
  d: path("M9.5 14h5v4h-5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.v4qx2ccfm {
  fill: currentColor;
  d: path("M8 7h8v4H8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.xgyiae7-j {
  d: path("M9.5 14h5v4h-5Z");
}

</style>
