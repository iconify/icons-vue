<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d-lcp_cyk"/><path class="f_j9o9own"/><path class="mn0t5mbsa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:deposit-money-market" /></template>
<style>
.d-lcp_cyk {
  d: path("M12.165 21H6.25q-.169.005-.337-.018q-.167-.023-.329-.074q-.161-.051-.311-.128q-.151-.077-.286-.179q-.136-.102-.252-.224t-.21-.264q-.095-.14-.164-.295T4.25 19.5l-1.75-7h9.9m6.2 0h1.5M5.5 8.25a3 1.25 0 1 0 6 0a3 1.25 0 1 0-6 0");
}

.f_j9o9own {
  d: path("M5.5 8.25V10c0 .75 1.25 1.25 3 1.25s3-.5 3-1.25V8.25m.75 0a3 1.25 0 1 0 6 0a3 1.25 0 1 0-6 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mn0t5mbsa {
  d: path("M12.25 8.25V10c0 .75 1.25 1.25 3 1.25s3-.5 3-1.25V8.25m-3.25 13L21.25 15m-7 .5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m5.25 5.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

</style>
