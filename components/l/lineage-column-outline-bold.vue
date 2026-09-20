<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="baerff2wm"/><path class="pmhsn037r"/><path class="qr1iqpomq"/><path class="zm2dyvb-o"/><path class="tkgsjrp5m"/><path class="i1uqf7jtv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:lineage-column-outline-bold" /></template>
<style>
.baerff2wm {
  d: path("M2 6a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.i1uqf7jtv {
  d: path("M17.5 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.pmhsn037r {
  d: path("M15 6a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

.qr1iqpomq {
  d: path("M9 8h6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tkgsjrp5m {
  d: path("M4.5 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.zm2dyvb-o {
  d: path("M9 16h6");
}

</style>
