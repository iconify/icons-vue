<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="konffhqhd"/><path class="rjb_q9q1l"/><path class="pmuiqo95v"/><path class="oqfv9rb9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:baggage-claim-outline-regular" /></template>
<style>
.konffhqhd {
  d: path("M6 6.5a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2V12a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oqfv9rb9x {
  d: path("M2 21h20");
}

.pmuiqo95v {
  d: path("M2 17h20");
}

.rjb_q9q1l {
  d: path("M10 4.5V2h4v2.5");
}

</style>
