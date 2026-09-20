<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bt8y9q_ij"/><path class="ovaa-tiew"/><path class="z5a_6pbxy"/><path class="awvlr1bio"/><path class="ucd8o6bjf"/><path class="nbncjhbtk"/><path class="qp5e0_b3n"/><path class="tdk6nzbaw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:event-stream-duotone-thin" /></template>
<style>
.awvlr1bio {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20.5 17v3.5H17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.bt8y9q_ij {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2.5 2.5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nbncjhbtk {
  d: path("M7.5 7.5 10 10");
}

.ovaa-tiew {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7.5 7.5 10 10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qp5e0_b3n {
  d: path("M12.5 12.5 15 15");
}

.tdk6nzbaw {
  d: path("M20.5 17v3.5H17");
}

.ucd8o6bjf {
  d: path("M2.5 2.5 5 5");
}

.z5a_6pbxy {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12.5 12.5 15 15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
