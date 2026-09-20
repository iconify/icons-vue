<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="m490zkdbl"/><path class="i2d4_-inn"/><path class="hazn09b_y"/><path class="t3o7icb6t"/><path class="v9n4_syfk"/><path class="hspeesv2z"/><path class="ujt25lh2u"/><path class="tv6hbrcra"/><path class="fyjgc24rp"/><path class="icp673bbo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:goal-filter-duotone-bold" /></template>
<style>
.fyjgc24rp {
  d: path("m9 6 3 3 3 -3");
}

.hazn09b_y {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8.5 20.5h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hspeesv2z {
  d: path("M5.5 3v5.5a6.5 6.5 0 0 0 13 0V3");
}

.i2d4_-inn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 15v5.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.icp673bbo {
  d: path("M12 9v3");
}

.m490zkdbl {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5.5 3v5.5a6.5 6.5 0 0 0 13 0V3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t3o7icb6t {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 6 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tv6hbrcra {
  d: path("M8.5 20.5h7");
}

.ujt25lh2u {
  d: path("M12 15v5.5");
}

.v9n4_syfk {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 9v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
