<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="q7l4tcb1c"/><path class="gsq10_ixg"/><path class="c4khiwgvb"/><path class="iq7hdacem"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hotel-check-out-outline-bold" /></template>
<style>
.c4khiwgvb {
  d: path("M8 15h8");
}

.gsq10_ixg {
  d: path("M7 6h4v3H7Z");
}

.iq7hdacem {
  d: path("M10.5 12.5 8 15l2.5 2.5");
}

.q7l4tcb1c {
  d: path("M6 3h11l4 4v12a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2V5a2 2 0 0 1 2 -2");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
