<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ovt_6acny"/><path class="p-570-pmk"/><path class="byh8rvbcw"/><path class="uci4f6n5q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:divide-broken" /></template>
<style>
.byh8rvbcw {
  d: path("M12 6H12.0001");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ovt_6acny {
  d: path("M4 12H12");
}

.p-570-pmk {
  d: path("M16 12H20");
}

.uci4f6n5q {
  d: path("M12 18H12.0001");
}

</style>
