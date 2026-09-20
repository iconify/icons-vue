<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ugdbidcqi"/><path class="o40l0bbgl"/><path class="arq593bkp"/><path class="mgbos9zve"/><path class="zpdz8rbaf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-timeout-outline-thin" /></template>
<style>
.arq593bkp {
  d: path("m9 9 6 6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mgbos9zve {
  d: path("m15 9 -6 6");
}

.o40l0bbgl {
  d: path("M9 8.5h6");
}

.ugdbidcqi {
  d: path("M16.23 2.94a10 10 0 1 1 -8.46 0");
}

.zpdz8rbaf {
  d: path("M9 15.5h6");
}

</style>
