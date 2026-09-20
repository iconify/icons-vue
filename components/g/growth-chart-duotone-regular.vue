<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gb7yzvvzz"/><path class="d0n0h67yq"/><path class="hfjew04rr"/><path class="qe97cg-lx"/><path class="dqeovmbtl"/><path class="fua3x2iyd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:growth-chart-duotone-regular" /></template>
<style>
.d0n0h67yq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m5 18 4 -4 3 3 7 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dqeovmbtl {
  d: path("m5 18 4 -4 3 3 7 -7");
}

.fua3x2iyd {
  d: path("M17 6h4");
}

.gb7yzvvzz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 3v18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hfjew04rr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 6h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qe97cg-lx {
  d: path("M3 3v18h18");
}

</style>
