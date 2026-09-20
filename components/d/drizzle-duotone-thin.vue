<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="esolkqbpc"/><path class="c-pcdbceg"/><path class="cfjjc4b9u"/><path class="luc_hlbxh"/><path class="k6xu7tbiy"/><path class="doij5pb5x"/><path class="p-vzdvbyx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:drizzle-duotone-thin" /></template>
<style>
.c-pcdbceg {
  d: path("M4 14a4 4 0 0 1 2 -7.5A5 5 0 0 1 15.5 5a5.5 5.5 0 0 1 4.5 9Z");
}

.cfjjc4b9u {
  d: path("m8 17 -2.5 2.5");
}

.doij5pb5x {
  d: path("M10.5 19.5 8 22");
}

.esolkqbpc {
  fill: currentColor;
  d: path("M4 14a4 4 0 0 1 2 -7.5A5 5 0 0 1 15.5 5a5.5 5.5 0 0 1 4.5 9Z");
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

.k6xu7tbiy {
  d: path("m18 17 -2.5 2.5");
}

.luc_hlbxh {
  d: path("m13 17 -2.5 2.5");
}

.p-vzdvbyx {
  d: path("M15.5 19.5 13 22");
}

</style>
