<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wv8_ljb3q"/><path class="l5f794mkz"/><path class="rw6ho_bav"/><path class="zmehrebyi"/><path class="zpiwxpb9e"/><path class="pi15tzbod"/><path class="c523ogurv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:health-card-duotone-regular" /></template>
<style>
.c523ogurv {
  d: path("M12 16h6");
}

.l5f794mkz {
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v11a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pi15tzbod {
  d: path("M12 12h8");
}

.rw6ho_bav {
  d: path("M2 9h20");
}

.wv8_ljb3q {
  fill: currentColor;
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v11a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zmehrebyi {
  d: path("M6 10.5v5");
}

.zpiwxpb9e {
  d: path("M3.5 13h5");
}

</style>
