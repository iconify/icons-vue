<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hhn64ub-m"/><path class="kv0b3x3qx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:demo-table" /></template>
<style>
.hhn64ub-m {
  d: path("M12.718 21.14q-.178.08-.368.119q-.191.039-.386.035t-.384-.051t-.363-.134l-7.25-3.625q-.108-.054-.208-.123t-.19-.151t-.167-.175t-.141-.197t-.113-.214t-.082-.228q-.033-.116-.049-.237Q3 16.039 3 15.918V8.082q0-.121.017-.241q.016-.121.049-.237q.033-.117.082-.228t.113-.214t.141-.197t.167-.175t.19-.151t.208-.123l7.25-3.625q.182-.091.381-.138q.198-.047.402-.047t.402.047t.381.138l7.25 3.625q.108.054.208.123t.19.151t.167.175t.141.197q.064.103.113.214t.082.228t.049.237q.017.12.017.241v6.554");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kv0b3x3qx {
  d: path("m3 7l9 4.5L21 7m-9 4.5v10M7.5 4.75l9 4.5m.711 6.441l1.836.988a1.5 1.5 0 0 1 0 2.642l-1.836.988A1.5 1.5 0 0 1 15 18.989v-1.978a1.5 1.5 0 0 1 2.211-1.32");
}

</style>
