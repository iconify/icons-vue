<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dh-nlhghu"/><path class="jiw8u-asa"/><path class="yavoltb2n"/><path class="m-5qbdc8e"/><path class="yoyflzbww"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="p86p59b-c"/><path class="d-23-qb2d"/><path class="ip4hr0bew"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-column-decreasing-duotone-bold" /></template>
<style>
.d-23-qb2d {
  d: path("M13 11v9");
}

.dh-nlhghu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ip4hr0bew {
  d: path("M18 15v5");
}

.jiw8u-asa {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m-5qbdc8e {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 11v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.p86p59b-c {
  d: path("M8 7v13");
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

.yavoltb2n {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 7v13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yoyflzbww {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 15v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
