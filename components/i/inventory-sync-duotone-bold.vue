<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hm52d9bxd"/><path class="gtj8b-brg"/><path class="yqnyzpgac"/><path class="mpsx05yxe"/><path class="e77gki8ci"/><path class="mvm7r4bea"/><path class="vlli8wboo"/><path class="yt5ezyvwf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:inventory-sync-duotone-bold" /></template>
<style>
.e77gki8ci {
  d: path("M2 20V10l3 -3h14l3 3v10");
}

.gtj8b-brg {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 14h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hm52d9bxd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 20V10l3 -3h14l3 3v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mpsx05yxe {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13.5 11.5 16 14l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mvm7r4bea {
  d: path("M8 14h8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vlli8wboo {
  d: path("M10.5 11.5 8 14l2.5 2.5");
}

.yqnyzpgac {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10.5 11.5 8 14l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yt5ezyvwf {
  d: path("M13.5 11.5 16 14l-2.5 2.5");
}

</style>
