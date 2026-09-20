<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w5o7xublt"/><path class="n9wp3eboj"/><path class="w_a7qw88f"/><path class="txii_1wlf"/><path class="zugrvnb7t"/><path class="t-oxscctn"/><path class="j08f9ezai"/><path class="dihddo_by"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:horizon-duotone-regular" /></template>
<style>
.dihddo_by {
  d: path("M6 18h12");
}

.j08f9ezai {
  d: path("m12 13 4 -4 4 4");
}

.n9wp3eboj {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m5 13 4 -4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t-oxscctn {
  d: path("m5 13 4 -4 4 4");
}

.txii_1wlf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 18h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w_a7qw88f {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m12 13 4 -4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w5o7xublt {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 13h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zugrvnb7t {
  d: path("M2 13h20");
}

</style>
