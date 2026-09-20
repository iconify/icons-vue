<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tp514yb1s"/><path class="lf5f-7bvs"/><path class="sjvxvsbmk"/><path class="ymccf7box"/><path class="f02t2vblf"/><path class="nkim8cbjd"/><path class="azgrucbqu"/><path class="j5yfc7b4j"/><path class="btdmtu_xg"/><path class="vckqcjbbb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:barcode-duotone-thin" /></template>
<style>
.azgrucbqu {
  d: path("M7 5v14");
}

.btdmtu_xg {
  d: path("M14 5v14");
}

.f02t2vblf {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j5yfc7b4j {
  d: path("M11 5v14");
}

.lf5f-7bvs {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nkim8cbjd {
  d: path("M4 5v14");
}

.sjvxvsbmk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tp514yb1s {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vckqcjbbb {
  d: path("M18 5v14");
}

.ymccf7box {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
