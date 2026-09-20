<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oa7csmxww"/><path class="uzf676bdq"/><path class="g49gmcc6t"/><path class="nvi1ntbbk"/><path class="a5qe4212t"/><path class="s-6a5ybts"/><path class="tkg_kabnx"/><path class="qnmmmsbha"/><path class="n7wfhbrgu"/><path class="scmqkut_d"/><path class="ngm_e1bgi"/><path class="jdz429b-z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:context-recall-duotone-thin" /></template>
<style>
.a5qe4212t {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 11.5 2 2 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g49gmcc6t {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 17h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jdz429b-z {
  d: path("m16 17.5 2 2 3 -3");
}

.n7wfhbrgu {
  d: path("M3 17h11");
}

.ngm_e1bgi {
  d: path("m16 11.5 2 2 3 -3");
}

.nvi1ntbbk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 5.5 2 2 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oa7csmxww {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 5h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qnmmmsbha {
  d: path("M3 11h11");
}

.s-6a5ybts {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 17.5 2 2 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.scmqkut_d {
  d: path("m16 5.5 2 2 3 -3");
}

.tkg_kabnx {
  d: path("M3 5h11");
}

.uzf676bdq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 11h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
