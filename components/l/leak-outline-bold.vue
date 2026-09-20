<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mqtixbwqo"/><path class="saqo5mbad"/><path class="mj3xlxbyp"/><path class="kgr7y94lw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:leak-outline-bold" /></template>
<style>
.kgr7y94lw {
  d: path("m12 13 2.5 2.5a3 3 0 1 1 -5 0Z");
}

.mj3xlxbyp {
  d: path("M14 5v6");
}

.mqtixbwqo {
  d: path("M2 8h20");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.saqo5mbad {
  d: path("M10 5v6");
}

</style>
