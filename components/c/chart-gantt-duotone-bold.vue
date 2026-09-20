<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dh-nlhghu"/><path class="jiw8u-asa"/><path class="ruxon9i9p"/><path class="map-hhy3d"/><path class="sum5xgbhm"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="r_r678bum"/><path class="lqiw_3bos"/><path class="xyhj-ubbr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-gantt-duotone-bold" /></template>
<style>
.dh-nlhghu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jiw8u-asa {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lqiw_3bos {
  d: path("M10 12h7");
}

.map-hhy3d {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 12h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.r_r678bum {
  d: path("M6 7h6");
}

.r3faxubne {
  d: path("M4 4v16");
}

.ruxon9i9p {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 7h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sum5xgbhm {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 17h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xyhj-ubbr {
  d: path("M13 17h7");
}

</style>
