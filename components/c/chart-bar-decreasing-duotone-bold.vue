<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dh-nlhghu"/><path class="jiw8u-asa"/><path class="n0m1ncd7n"/><path class="kidjoqbxn"/><path class="fcgs54bdg"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="xeoeqgblt"/><path class="yw-dgs_nk"/><path class="vjfpd3ony"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-bar-decreasing-duotone-bold" /></template>
<style>
.dh-nlhghu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fcgs54bdg {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 17h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jiw8u-asa {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kidjoqbxn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.n0m1ncd7n {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 7h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.r3faxubne {
  d: path("M4 4v16");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vjfpd3ony {
  d: path("M4 17h6");
}

.xeoeqgblt {
  d: path("M4 7h14");
}

.yw-dgs_nk {
  d: path("M4 12h10");
}

</style>
