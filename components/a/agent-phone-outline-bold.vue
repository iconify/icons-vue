<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="skbifdbcx"/><path class="kevu0gbpg"/><path class="izycrzbmp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-phone-outline-bold" /></template>
<style>
.izycrzbmp {
  d: path("M16 14h3");
}

.kevu0gbpg {
  d: path("M14 13a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.skbifdbcx {
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
}

</style>
