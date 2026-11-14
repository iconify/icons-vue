<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z4w_d6tcv"/><path class="tnktjj06t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:broadcast-tower-settings" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tnktjj06t {
  d: path("m6.5 21.5l5.5-13l2.137 5.051M16 3.5a4.5 4.5 0 0 1 0 6m3-7a8 8 0 0 1 0 8m-11-7a4.5 4.5 0 0 0 0 6m-3-7a8 8 0 0 0 0 8m12.398 4.82za.546.546 0 0 1 .546-.519h.112a.546.546 0 0 1 .546.519a.96.96 0 0 0 .476.779l.029.017a.96.96 0 0 0 .913.023a.546.546 0 0 1 .722.213l.056.097a.546.546 0 0 1-.177.732a.96.96 0 0 0-.436.802v.034a.96.96 0 0 0 .436.802a.546.546 0 0 1 .177.732l-.056.097a.546.546 0 0 1-.722.213a.96.96 0 0 0-.913.023l-.029.017a.96.96 0 0 0-.476.779a.546.546 0 0 1-.546.519h-.112a.546.546 0 0 1-.546-.519a.96.96 0 0 0-.476-.779l-.029-.017a.96.96 0 0 0-.913-.023a.546.546 0 0 1-.722-.213l-.056-.097a.546.546 0 0 1 .177-.732a.96.96 0 0 0 .436-.802v-.034a.96.96 0 0 0-.436-.802a.546.546 0 0 1-.177-.732l.056-.097a.546.546 0 0 1 .722-.213a.96.96 0 0 0 .913-.023l.029-.017a.96.96 0 0 0 .476-.779");
}

.z4w_d6tcv {
  d: path("M10 6.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
