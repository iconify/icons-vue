<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nwkidzbbg"/><path class="sfrizzcif"/><path class="x7ap30bft"/><path class="jq33rvbor"/><path class="ma01ysb5t"/><path class="uxyzhxvwz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:fasting-window-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jq33rvbor {
  d: path("M6 7H3v10h3");
}

.ma01ysb5t {
  d: path("M18 7h3v10h-3");
}

.nwkidzbbg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 7H3v10h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.sfrizzcif {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 7h3v10h-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uxyzhxvwz {
  d: path("M7 12h10");
}

.x7ap30bft {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
