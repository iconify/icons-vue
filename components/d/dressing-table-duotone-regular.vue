<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lyp1l130n"/><path class="njnz25bwe"/><path class="bx3fv3b8c"/><path class="pmuiqo95v"/><path class="vdy_x0b6n"/><path class="oquq7bbql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dressing-table-duotone-regular" /></template>
<style>
.bx3fv3b8c {
  d: path("M12 13v4");
}

.lyp1l130n {
  fill: currentColor;
  d: path("M8 8a4 5 0 1 1 8 0 4 5 0 1 1 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.njnz25bwe {
  d: path("M8 8a4 5 0 1 1 8 0 4 5 0 1 1 -8 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oquq7bbql {
  d: path("M20 17v4");
}

.pmuiqo95v {
  d: path("M2 17h20");
}

.vdy_x0b6n {
  d: path("M4 17v4");
}

</style>
