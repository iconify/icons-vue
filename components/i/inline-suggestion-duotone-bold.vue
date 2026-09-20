<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="khksl7boy"/><path class="sf_49krow"/><path class="n_wlgzbnq"/><path class="be2wnib8t"/><path class="c75csrozg"/><path class="xgrfb-bqu"/><path class="pesxdybze"/><path class="etqzyebuj"/><path class="y7_y8yq8z"/><path class="tb33trnmj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:inline-suggestion-duotone-bold" /></template>
<style>
.be2wnib8t {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18.5 12H21");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.c75csrozg {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 18h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.etqzyebuj {
  d: path("M13 12h2.5");
}

.khksl7boy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.n_wlgzbnq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 12h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pesxdybze {
  d: path("M3 12h7");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sf_49krow {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 12h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tb33trnmj {
  d: path("M3 18h5");
}

.xgrfb-bqu {
  d: path("M3 6h18");
}

.y7_y8yq8z {
  d: path("M18.5 12H21");
}

</style>
