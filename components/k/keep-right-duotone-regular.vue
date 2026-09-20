<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j7sj82kwz"/><path class="vgq1lnv0l"/><path class="lz5i7ta_k"/><path class="bp3yu1oem"/><path class="d0n0p9bwt"/><path class="mz0o03tol"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:keep-right-duotone-regular" /></template>
<style>
.bp3yu1oem {
  d: path("M12 22v-9l7 -7");
}

.d0n0p9bwt {
  d: path("M19 10.5V6h-4.5");
}

.j7sj82kwz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 22v-9l7 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lz5i7ta_k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 11 5 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mz0o03tol {
  d: path("M10 11 5 6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vgq1lnv0l {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M19 10.5V6h-4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
