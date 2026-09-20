<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="igf1wdb1b"/><path class="soc05fb5m"/><path class="episydb5i"/><path class="w77w8cbyi"/><path class="r3uz_wvor"/><path class="vvv_0v-7b"/><path class="auc4o2swl"/><path class="bu35rpbki"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hammock-duotone-thin" /></template>
<style>
.auc4o2swl {
  d: path("M4 8c0 8 16 8 16 0");
}

.bu35rpbki {
  d: path("M4 12c0 7 16 7 16 0");
}

.episydb5i {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 8c0 8 16 8 16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.igf1wdb1b {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 6v15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3uz_wvor {
  d: path("M4 6v15");
}

.soc05fb5m {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 6v15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vvv_0v-7b {
  d: path("M20 6v15");
}

.w77w8cbyi {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 12c0 7 16 7 16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
