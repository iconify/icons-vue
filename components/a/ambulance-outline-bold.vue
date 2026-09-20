<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c4qbjsqib"/><path class="koh8ckbdb"/><path class="k2mg4f2ls"/><path class="nx7-m9bik"/><path class="uok3uci1j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ambulance-outline-bold" /></template>
<style>
.c4qbjsqib {
  d: path("M2 17V8a2 2 0 0 1 2 -2h10v4h3.5l3.5 3.5V17Z");
}

.k2mg4f2ls {
  d: path("M15 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.koh8ckbdb {
  d: path("M5 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.nx7-m9bik {
  d: path("M8 9v4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uok3uci1j {
  d: path("M6 11h4");
}

</style>
