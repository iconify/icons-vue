<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="arrxut8vu"/><path class="nr2kwkbiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:loan-write-off" /></template>
<style>
.arrxut8vu {
  d: path("m11.503 16.154l-.768.768q-.091.091-.191.173t-.207.153t-.221.133t-.233.11t-.242.087q-.123.037-.25.062q-.126.025-.255.038q-.128.013-.257.013t-.257-.013t-.255-.038t-.25-.062t-.242-.087t-.233-.11t-.221-.133q-.107-.071-.207-.153t-.191-.173l-1.945-1.945q-.091-.091-.173-.191t-.153-.207t-.133-.221q-.061-.113-.11-.233q-.049-.119-.087-.242t-.062-.25q-.025-.126-.038-.255q-.013-.128-.013-.257t.013-.257t.038-.255t.062-.25q.038-.123.087-.242q.049-.12.11-.233t.133-.221q.071-.107.153-.207t.173-.191l6.187-6.187q.091-.091.191-.173t.207-.153t.221-.133t.233-.11q.119-.049.242-.087t.25-.062q.126-.025.255-.038q.128-.013.257-.013t.257.013t.255.038t.25.062q.123.038.242.087q.12.049.233.11t.221.133q.107.071.207.153t.191.173l1.945 1.945q.091.091.173.191t.153.207t.133.221t.11.233t.087.242t.062.25t.038.255t.013.257q0 .129-.013.257q-.013.129-.038.255q-.025.127-.062.25q-.038.123-.087.242q-.049.12-.11.233t-.133.221t-.153.207t-.173.191l-1.813 1.813M6.404 9.939l5.445 5.445M3 20.5h6m5-2.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nr2kwkbiv {
  d: path("M17 15h2a3 3 0 0 1 0 6h-2");
}

</style>
