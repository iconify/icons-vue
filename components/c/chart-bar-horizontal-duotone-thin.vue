<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gms_xv68n"/><path class="yu-j7jb_g"/><path class="d34cl1b_x"/><path class="hmjrplfvq"/><path class="qiomh5b_o"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="f-mjnibpi"/><path class="w6105m-jv"/><path class="nwor_i7ms"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-bar-horizontal-duotone-thin" /></template>
<style>
.d34cl1b_x {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 7h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f-mjnibpi {
  d: path("M4 7h12");
}

.gms_xv68n {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hmjrplfvq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nwor_i7ms {
  d: path("M4 17h14");
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.qiomh5b_o {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 17h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3faxubne {
  d: path("M4 4v16");
}

.w6105m-jv {
  d: path("M4 12h8");
}

.yu-j7jb_g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
