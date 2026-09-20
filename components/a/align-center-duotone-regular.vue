<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="be306ynmy"/><path class="jvklyhryq"/><path class="zpba4e-4d"/><path class="xgrfb-bqu"/><path class="qt4afwy9g"/><path class="ite_ehtoh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:align-center-duotone-regular" /></template>
<style>
.be306ynmy {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ite_ehtoh {
  d: path("M4.5 18h15");
}

.jvklyhryq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6.5 12h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qt4afwy9g {
  d: path("M6.5 12h11");
}

.xgrfb-bqu {
  d: path("M3 6h18");
}

.zpba4e-4d {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4.5 18h15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
