<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="aylp_vm5a"/><path class="w5ulzabke"/><path class="yww07mbhe"/><path class="xaz90clio"/><path class="giopbjb9g"/><path class="h_alycbda"/><path class="lb5uptbbe"/><path class="rkhcgsbdl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:grass-duotone-bold" /></template>
<style>
.aylp_vm5a {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 19v-7l3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.giopbjb9g {
  d: path("M5 19v-7l3 -3");
}

.h_alycbda {
  d: path("M10 19v-9l3 -3");
}

.lb5uptbbe {
  d: path("M16 19v-7l3 -3");
}

.rkhcgsbdl {
  d: path("M3 19h18");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.w5ulzabke {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 19v-9l3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xaz90clio {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 19h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yww07mbhe {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 19v-7l3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
