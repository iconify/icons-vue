<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="trirghiqk"/><path class="rdvmv8b4c"/><path class="u03cdlbzd"/><path class="wtdeoydrz"/><path class="mqtixbwqo"/><path class="yam3-1b2z"/><path class="mei2sobow"/><path class="xmopbdc-t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:coffee-table-duotone-bold" /></template>
<style>
.mei2sobow {
  d: path("M19 8v12");
}

.mqtixbwqo {
  d: path("M2 8h20");
}

.rdvmv8b4c {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.trirghiqk {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 8h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.u03cdlbzd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wtdeoydrz {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 15h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xmopbdc-t {
  d: path("M5 15h14");
}

.yam3-1b2z {
  d: path("M5 8v12");
}

</style>
