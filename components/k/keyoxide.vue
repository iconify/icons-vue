<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="m9t9o5bpv"/><circle class="bvy-k9bfe"/><circle class="rq9_dya8u"/><path class="lvek-ebkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:keyoxide" /></template>
<style>
.bvy-k9bfe {
  cx: 25.188px;
  cy: 6.478px;
  r: 0.977px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.lvek-ebkw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.75 34.862l-8.498-6.356l8.498-6.355a4.85 4.85 0 0 0 .979-6.79a5 5 0 0 0-.36-.42a1.646 1.646 0 1 0-2.099-1.292a4.9 4.9 0 0 0-1.951-.185a2.594 2.594 0 1 0-2.729 1.18l-5.585 4.177v-.555a4.85 4.85 0 1 0-9.7 0v20.48a4.85 4.85 0 1 0 9.7 0v-.554l5.935 4.438a4.85 4.85 0 1 0 5.81-7.768");
}

.m9t9o5bpv {
  cx: 23.038px;
  cy: 9.886px;
  r: 1.363px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rq9_dya8u {
  cx: 22.288px;
  cy: 5.153px;
  r: 0.75px;
  fill: currentColor;
}

</style>
