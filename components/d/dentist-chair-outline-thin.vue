<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dzbcwvq-w"/><path class="itq_ntb3g"/><path class="gv5aqrbwu"/><path class="n53lfdc0t"/><path class="pkt304bvs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dentist-chair-outline-thin" /></template>
<style>
.dzbcwvq-w {
  d: path("M3 16v-4h16v4Z");
}

.gv5aqrbwu {
  d: path("M7 21h8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.itq_ntb3g {
  d: path("M11 16v5");
}

.n53lfdc0t {
  d: path("M16 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.pkt304bvs {
  d: path("M19 8v4");
}

</style>
