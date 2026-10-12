<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v14frkb3x"/><circle class="t-earhali"/><path class="ibi699bkp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:achievement" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ibi699bkp {
  d: path("m12.13 12.57l.53 1.26q.13.33.48.36l1.36.1q.35.03.09.26l-1.04.89q-.27.23-.18.57l.31 1.33q.08.34-.22.15l-1.16-.71q-.3-.18-.6 0l-1.16.71q-.3.19-.22-.15l.31-1.33q.09-.34-.18-.57l-1.04-.89q-.26-.23.09-.26l1.36-.1q.35-.03.48-.36l.53-1.26q.13-.32.26 0");
}

.t-earhali {
  cx: 12px;
  cy: 15px;
  r: 6px;
}

.v14frkb3x {
  d: path("m7.85 10.05l-2.2-6.82q-.15-.48.35-.48h2.25q.5 0 .63.48l1.49 5.48q.13.48-.31.72l-1.62.86q-.44.24-.59-.24m8.3 0l2.2-6.82q.15-.48-.35-.48h-2.25q-.5 0-.63.48l-1.49 5.48q-.13.48.31.72l1.62.86q.44.24.59-.24");
}

</style>
