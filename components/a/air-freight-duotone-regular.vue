<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uobmn7udv"/><path class="btl8y2bhn"/><path class="cx2wb--vw"/><path class="gqm813tpr"/><path class="oadftbbjm"/><path class="ae-e09b3w"/><path class="d26wznbgp"/><path class="wm3q5wbwg"/><path class="vblyu6b4h"/><path class="r3snlms8q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:air-freight-duotone-regular" /></template>
<style>
.ae-e09b3w {
  d: path("M3 12h18");
}

.btl8y2bhn {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 12 7 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cx2wb--vw {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m13 12 -6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d26wznbgp {
  d: path("M13 12 7 6");
}

.gqm813tpr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m5 12 -2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oadftbbjm {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m5 12 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3snlms8q {
  d: path("m5 12 -2 2");
}

.uobmn7udv {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 12h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vblyu6b4h {
  d: path("m5 12 -2 -2");
}

.wm3q5wbwg {
  d: path("m13 12 -6 6");
}

</style>
