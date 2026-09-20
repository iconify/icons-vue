<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jzeve79sx"/><path class="ovtnh7b1i"/><path class="pgh99fbrg"/><path class="drdh7jc7j"/><path class="owegdrbfc"/><path class="ymw3aibdo"/><path class="mhnr27bap"/><path class="fx4s06o2o"/><path class="cwioy_h_g"/><path class="nggq41d_a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:explain-plan-duotone-regular" /></template>
<style>
.cwioy_h_g {
  d: path("M4 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.drdh7jc7j {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 7v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fx4s06o2o {
  d: path("M6 13v-3h12v3");
}

.jzeve79sx {
  fill: currentColor;
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.mhnr27bap {
  d: path("M12 7v3");
}

.nggq41d_a {
  d: path("M16 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ovtnh7b1i {
  fill: currentColor;
  d: path("M4 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.owegdrbfc {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 13v-3h12v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pgh99fbrg {
  fill: currentColor;
  d: path("M16 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ymw3aibdo {
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
