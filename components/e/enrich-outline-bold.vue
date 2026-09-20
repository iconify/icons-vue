<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="inp0fub_p"/><path class="rh_i50bzs"/><path class="d5yu6lbvq"/><path class="pkt304bvs"/><path class="l8vricc3a"/><path class="rjbfcabog"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:enrich-outline-bold" /></template>
<style>
.d5yu6lbvq {
  d: path("M4 14h9");
}

.inp0fub_p {
  d: path("M2 6a2 2 0 0 1 2 -2h9a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.l8vricc3a {
  d: path("M17 10h4");
}

.pkt304bvs {
  d: path("M19 8v4");
}

.rh_i50bzs {
  d: path("M4 9h9");
}

.rjbfcabog {
  d: path("M17 16h4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
