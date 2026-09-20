<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kf3muskvz"/><path class="wgplwsbmx"/><path class="vqal-abhe"/><path class="bpdfs5b6a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:health-probe-duotone-thin" /></template>
<style>
.bpdfs5b6a {
  d: path("m9 15 2 2 4 -4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kf3muskvz {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 8h4.5l2 -2 4 4 2 -2H21");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vqal-abhe {
  d: path("M3 8h4.5l2 -2 4 4 2 -2H21");
}

.wgplwsbmx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 15 2 2 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
