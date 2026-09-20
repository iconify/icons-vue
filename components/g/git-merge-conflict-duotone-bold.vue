<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qecovn3xi"/><path class="ujw6lacqu"/><path class="y3a01mblb"/><path class="ly22j4qka"/><path class="ywss1s28h"/><path class="xfmqtvi8p"/><path class="kn0tcm93r"/><path class="jg5k_rbda"/><path class="dhp6n31qa"/><path class="gjb6r-bki"/><path class="x8v9hpbcn"/><path class="qe18cgb-r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:git-merge-conflict-duotone-bold" /></template>
<style>
.dhp6n31qa {
  d: path("M6 7.5V12l4.5 4.5");
}

.gjb6r-bki {
  d: path("M18 7.5V12l-4.5 4.5");
}

.jg5k_rbda {
  d: path("M16 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.kn0tcm93r {
  d: path("M4 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.ly22j4qka {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 7.5V12l-4.5 4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qe18cgb-r {
  d: path("m14.5 16.5 -5 5");
}

.qecovn3xi {
  fill: currentColor;
  d: path("M4 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ujw6lacqu {
  fill: currentColor;
  d: path("M16 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.x8v9hpbcn {
  d: path("m9.5 16.5 5 5");
}

.xfmqtvi8p {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m14.5 16.5 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y3a01mblb {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 7.5V12l4.5 4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ywss1s28h {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9.5 16.5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
