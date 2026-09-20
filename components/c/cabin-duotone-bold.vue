<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ga65sabzo"/><path class="e95s_yp3q"/><path class="r770zptwl"/><path class="dzga-4bqj"/><path class="a6e_o0bju"/><path class="dvfmj91gv"/><path class="nl66y9men"/><path class="l4quinbfm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cabin-duotone-bold" /></template>
<style>
.a6e_o0bju {
  d: path("m3 11 9 -9 9 9");
}

.dvfmj91gv {
  d: path("M6 11v10h12V11");
}

.dzga-4bqj {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 6V3h3v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e95s_yp3q {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 11v10h12V11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ga65sabzo {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 11 9 -9 9 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l4quinbfm {
  d: path("M16 6V3h3v3");
}

.nl66y9men {
  d: path("M6 16h12");
}

.r770zptwl {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 16h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
