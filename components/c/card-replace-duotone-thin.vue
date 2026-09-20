<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f-t_rcb_j"/><path class="k6fi9qmtq"/><path class="ozi-k-boi"/><path class="mvm7r4bea"/><path class="vlli8wboo"/><path class="yt5ezyvwf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:card-replace-duotone-thin" /></template>
<style>
.f-t_rcb_j {
  fill: currentColor;
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k6fi9qmtq {
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.mvm7r4bea {
  d: path("M8 14h8");
}

.ozi-k-boi {
  d: path("M3 7h18");
}

.vlli8wboo {
  d: path("M10.5 11.5 8 14l2.5 2.5");
}

.yt5ezyvwf {
  d: path("M13.5 11.5 16 14l-2.5 2.5");
}

</style>
