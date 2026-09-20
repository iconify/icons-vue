<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gcurcebny"/><path class="bo51iypxr"/><path class="u8rhnqeij"/><path class="gb5wfqbem"/><path class="ylrhsngsk"/><path class="or09jiblq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:helm-chart-outline-thin" /></template>
<style>
.bo51iypxr {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.gb5wfqbem {
  d: path("M12 19v2.5");
}

.gcurcebny {
  d: path("M6 12a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.or09jiblq {
  d: path("M19 12h2.5");
}

.u8rhnqeij {
  d: path("M12 2.5V5");
}

.ylrhsngsk {
  d: path("M2.5 12H5");
}

</style>
