<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vul_uwbfe"/><path class="xl0-albli"/><path class="l-gv5l26x"/><path class="tdej10bmv"/><path class="z7j5ddc1b"/><path class="nrqy16b7j"/><path class="em798y7rn"/><path class="pvfbz5b4i"/><path class="wy-zn0bse"/><path class="e9z836b7m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:blizzard-duotone-regular" /></template>
<style>
.e9z836b7m {
  d: path("M18.5 15v6m-3 0 6 -6");
}

.em798y7rn {
  d: path("M6 12h14");
}

.l-gv5l26x {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 18h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nrqy16b7j {
  d: path("M3 6h11");
}

.pvfbz5b4i {
  d: path("M3 18h11");
}

.tdej10bmv {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18.5 3v6m-3 0 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vul_uwbfe {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 6h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wy-zn0bse {
  d: path("M18.5 3v6m-3 0 6 -6");
}

.xl0-albli {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 12h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z7j5ddc1b {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18.5 15v6m-3 0 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
