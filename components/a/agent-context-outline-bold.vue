<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="skbifdbcx"/><path class="qn5d-0b_j"/><path class="jkpgw6k5z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-context-outline-bold" /></template>
<style>
.jkpgw6k5z {
  d: path("M19.5 12H22v9h-2.5");
}

.qn5d-0b_j {
  d: path("M14.5 12H12v9h2.5");
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
