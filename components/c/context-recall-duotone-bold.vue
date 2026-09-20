<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="s0sz1tb6l"/><path class="es4r-tbix"/><path class="s6ccfofjv"/><path class="rqjc25hmz"/><path class="n1cfk6bpl"/><path class="g4bafjtub"/><path class="tkg_kabnx"/><path class="qnmmmsbha"/><path class="n7wfhbrgu"/><path class="scmqkut_d"/><path class="ngm_e1bgi"/><path class="jdz429b-z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:context-recall-duotone-bold" /></template>
<style>
.es4r-tbix {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 11h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g4bafjtub {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m16 17.5 2 2 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jdz429b-z {
  d: path("m16 17.5 2 2 3 -3");
}

.n1cfk6bpl {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m16 11.5 2 2 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.n7wfhbrgu {
  d: path("M3 17h11");
}

.ngm_e1bgi {
  d: path("m16 11.5 2 2 3 -3");
}

.qnmmmsbha {
  d: path("M3 11h11");
}

.rqjc25hmz {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m16 5.5 2 2 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s0sz1tb6l {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 5h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s6ccfofjv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 17h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.scmqkut_d {
  d: path("m16 5.5 2 2 3 -3");
}

.tkg_kabnx {
  d: path("M3 5h11");
}

</style>
