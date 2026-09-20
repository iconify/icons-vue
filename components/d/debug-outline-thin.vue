<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t12-ippwj"/><path class="okx82l_9n"/><path class="b6v15s2sv"/><path class="tjrb92etf"/><path class="zdgbjmbif"/><path class="gc_u7gkmh"/><path class="aq5ydbtto"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:debug-outline-thin" /></template>
<style>
.aq5ydbtto {
  d: path("m16 5 -2.5 2.5");
}

.b6v15s2sv {
  d: path("M16.5 11H21");
}

.gc_u7gkmh {
  d: path("m8 5 2.5 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.okx82l_9n {
  d: path("M3 11h4.5");
}

.t12-ippwj {
  d: path("M7 13a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

.tjrb92etf {
  d: path("M3 15h4.5");
}

.zdgbjmbif {
  d: path("M16.5 15H21");
}

</style>
