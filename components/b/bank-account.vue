<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="utxqdi0vh"/><circle class="opd1rb5sr"/><path class="ryyhgna5c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bank-account" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.opd1rb5sr {
  cx: 17.5px;
  cy: 13.75px;
  r: 2px;
}

.ryyhgna5c {
  d: path("M13.75 21.25a3.75 3.75 0 0 1 7.5 0");
}

.utxqdi0vh {
  d: path("m3.55 7.65l5.15-3.8q.8-.6 1.6 0l5.15 3.8q.8.6-.2.6H3.75q-1 0-.2-.6M5.25 11v5.5M9.5 11v5.5m-6.75 3H12");
}

</style>
