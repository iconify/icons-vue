<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dh-nlhghu"/><path class="jiw8u-asa"/><path class="ugbe9qb8h"/><path class="m-5qbdc8e"/><path class="kg-25jupx"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="x0cr3vblz"/><path class="d-23-qb2d"/><path class="gacdnhbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-column-increasing-duotone-bold" /></template>
<style>
.d-23-qb2d {
  d: path("M13 11v9");
}

.dh-nlhghu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gacdnhbnq {
  d: path("M18 7v13");
}

.jiw8u-asa {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kg-25jupx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 7v13");
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

.ugbe9qb8h {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 15v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x0cr3vblz {
  d: path("M8 15v5");
}

</style>
