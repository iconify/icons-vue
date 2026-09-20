<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i7z0vob4i"/><path class="xhfvy9skf"/><path class="pc2zumbrl"/><path class="xbz1ymhpu"/><path class="xf07dvr8m"/><path class="ml3aqbbkk"/><path class="rw2cw9fuy"/><path class="pq2hynbuc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bandwidth-cap-duotone-regular" /></template>
<style>
.i7z0vob4i {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 5h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ml3aqbbkk {
  d: path("M4 8v12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pc2zumbrl {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20h17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pq2hynbuc {
  d: path("m6 18 4 -4 3 3 6 -6");
}

.rw2cw9fuy {
  d: path("M4 20h17");
}

.xbz1ymhpu {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m6 18 4 -4 3 3 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xf07dvr8m {
  d: path("M2 5h20");
}

.xhfvy9skf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
