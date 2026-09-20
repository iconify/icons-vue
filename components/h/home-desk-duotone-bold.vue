<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ded97twic"/><path class="ogsy_iyfo"/><path class="rh0xrcajx"/><path class="uekn-bn9g"/><path class="l0iv52bbj"/><path class="kamdbib6v"/><path class="v-q4myyjv"/><path class="n2ya_p02p"/><path class="h5yksf4iw"/><path class="e3fkgnlsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:home-desk-duotone-bold" /></template>
<style>
.ded97twic {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 7h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e3fkgnlsf {
  d: path("M13 16h7");
}

.h5yksf4iw {
  d: path("M13 12h7");
}

.kamdbib6v {
  d: path("M2 7h20");
}

.l0iv52bbj {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 16h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.n2ya_p02p {
  d: path("M13 7v13h7V7");
}

.ogsy_iyfo {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 7v13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rh0xrcajx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 7v13h7V7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uekn-bn9g {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 12h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v-q4myyjv {
  d: path("M4 7v13");
}

</style>
