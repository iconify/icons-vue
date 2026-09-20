<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kf3k8pbxe"/><path class="h737ebc_s"/><path class="u4eh83btt"/><path class="yfyg0bb3p"/><path class="snqsppb6q"/><path class="atoje4bsc"/><path class="njj_4bcir"/><path class="xj193cz1p"/><path class="e948j-b5x"/><path class="pmuiqo95v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:balcony-duotone-regular" /></template>
<style>
.atoje4bsc {
  d: path("M2 6h20");
}

.e948j-b5x {
  d: path("M18 6v11");
}

.h737ebc_s {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 6v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kf3k8pbxe {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 6h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.njj_4bcir {
  d: path("M6 6v11");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pmuiqo95v {
  d: path("M2 17h20");
}

.snqsppb6q {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 17h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.u4eh83btt {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 6v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xj193cz1p {
  d: path("M12 6v11");
}

.yfyg0bb3p {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 6v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
