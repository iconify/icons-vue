<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sjl2a_b7v"/><path class="or1d194jp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:label-applicator" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.or1d194jp {
  d: path("m3 7l9 4.5L21 7m-9 4.5v5.4m0 2.2v2.4M7.5 4.75l9 4.5m-1.333 7.741l1.137-1.25a1.5 1.5 0 0 1 1.11-.491h2.836a1.5 1.5 0 0 1 1.5 1.5v2.5a1.5 1.5 0 0 1-1.5 1.5h-2.836a1.5 1.5 0 0 1-1.11-.491l-1.137-1.25a1.5 1.5 0 0 1 0-2.018M17 18h.01");
}

.sjl2a_b7v {
  d: path("m13.166 20.917l-.383.192q-.182.091-.381.138q-.198.047-.402.047t-.402-.047t-.381-.138l-7.25-3.625q-.108-.054-.208-.123t-.19-.151t-.167-.175t-.141-.197t-.113-.214t-.082-.228q-.033-.116-.049-.237Q3 16.039 3 15.918V8.082q0-.121.017-.241q.016-.121.049-.237q.033-.117.082-.228t.113-.214t.141-.197t.167-.175t.19-.151t.208-.123l7.25-3.625q.182-.091.381-.138q.198-.047.402-.047t.402.047t.381.138l7.25 3.625q.108.054.208.123t.19.151t.167.175t.141.197q.064.103.113.214t.082.228t.049.237q.017.12.017.241v4.454");
}

</style>
