<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xq1pi7btv"/><path class="sib4g3mzz"/><path class="jt7d488ke"/><path class="j4nym3cre"/><path class="bmr2oqbjx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:food-chain-outline-thin" /></template>
<style>
.bmr2oqbjx {
  d: path("m14 10 2 -2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j4nym3cre {
  d: path("m6 16 2 -2");
}

.jt7d488ke {
  d: path("M13 7a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.sib4g3mzz {
  d: path("M7 13a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.xq1pi7btv {
  d: path("M2 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
