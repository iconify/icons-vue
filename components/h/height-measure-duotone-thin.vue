<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g6n49udox"/><path class="corfxhbfm"/><path class="fa20jgbno"/><path class="t8qgc60qv"/><path class="ck_r08b8b"/><path class="h2-2dgnfu"/><path class="tdul-wdwn"/><path class="vy337188j"/><path class="rjrs_5bsc"/><path class="xslfg2evh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:height-measure-duotone-thin" /></template>
<style>
.ck_r08b8b {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 21h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.corfxhbfm {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 6 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fa20jgbno {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 18 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g6n49udox {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h2-2dgnfu {
  d: path("M12 3v18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rjrs_5bsc {
  d: path("M6 3h12");
}

.t8qgc60qv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 3h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tdul-wdwn {
  d: path("m9 6 3 -3 3 3");
}

.vy337188j {
  d: path("m9 18 3 3 3 -3");
}

.xslfg2evh {
  d: path("M6 21h12");
}

</style>
