<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="earhjk-cy"/><path class="z-znvccxj"/><path class="sg9u-_b9e"/><path class="xgrfb-bqu"/><path class="tee3b-ble"/><path class="kp3vwzbyx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:align-right-duotone-thin" /></template>
<style>
.earhjk-cy {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kp3vwzbyx {
  d: path("M6 18h15");
}

.sg9u-_b9e {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 18h15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tee3b-ble {
  d: path("M10 12h11");
}

.xgrfb-bqu {
  d: path("M3 6h18");
}

.z-znvccxj {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 12h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
