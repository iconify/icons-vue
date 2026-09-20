<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="txe4klbyh"/><path class="plajqrbag"/><path class="mv9_3430k"/><path class="p3mg9-e5m"/><path class="dt4wyoqho"/><path class="fz6e7vbzb"/><path class="dc0xg9bgf"/><path class="zqnyy8bad"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:filter-metadata-duotone-thin" /></template>
<style>
.dc0xg9bgf {
  d: path("M9 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.dt4wyoqho {
  d: path("M9 4H3l7 7v7h4v-7l7 -7h-6");
}

.fz6e7vbzb {
  d: path("M5 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mv9_3430k {
  fill: currentColor;
  d: path("M13 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.p3mg9-e5m {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 4H3l7 7v7h4v-7l7 -7h-6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.plajqrbag {
  fill: currentColor;
  d: path("M9 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.txe4klbyh {
  fill: currentColor;
  d: path("M5 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zqnyy8bad {
  d: path("M13 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
