<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tuk2cgbpz"/><path class="tg5bh2bez"/><path class="gk3i4ixfw"/><path class="bv1y61bvs"/><path class="ils7yp4cg"/><path class="v2r_pnsln"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:all-inclusive-duotone-regular" /></template>
<style>
.bv1y61bvs {
  d: path("M4 16a8 8 0 0 1 16 0");
}

.gk3i4ixfw {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m8 9 3 3 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ils7yp4cg {
  d: path("M2 16h20");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tg5bh2bez {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 16h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tuk2cgbpz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 16a8 8 0 0 1 16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v2r_pnsln {
  d: path("m8 9 3 3 5 -5");
}

</style>
