<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xgrfb-bqu"/><path class="sprybdcan"/><path class="xsa445osm"/><path class="w7sxxlcqv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:a-record-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sprybdcan {
  d: path("M3 15a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.w7sxxlcqv {
  d: path("m18 12 3 3 -3 3");
}

.xgrfb-bqu {
  d: path("M3 6h18");
}

.xsa445osm {
  d: path("M9 15h7");
}

</style>
