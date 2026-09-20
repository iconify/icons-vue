<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nwi87ac4g"/><path class="e8rfc8bkg"/><path class="abanl_bku"/><path class="b8byr4b5i"/><path class="e77gki8ci"/><path class="mvm7r4bea"/><path class="vlli8wboo"/><path class="yt5ezyvwf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:inventory-sync-duotone-thin" /></template>
<style>
.abanl_bku {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10.5 11.5 8 14l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.b8byr4b5i {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13.5 11.5 16 14l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e77gki8ci {
  d: path("M2 20V10l3 -3h14l3 3v10");
}

.e8rfc8bkg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 14h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mvm7r4bea {
  d: path("M8 14h8");
}

.nwi87ac4g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 20V10l3 -3h14l3 3v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vlli8wboo {
  d: path("M10.5 11.5 8 14l2.5 2.5");
}

.yt5ezyvwf {
  d: path("M13.5 11.5 16 14l-2.5 2.5");
}

</style>
