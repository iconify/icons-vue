<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="guvqp3f2r"/><path class="cxuxqq_-d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:laptop-settings" /></template>
<style>
.cxuxqq_-d {
  d: path("M11.398 7.32za.546.546 0 0 1 .546-.519h.112a.546.546 0 0 1 .546.519a.96.96 0 0 0 .476.779l.029.017a.96.96 0 0 0 .913.023a.546.546 0 0 1 .722.213l.056.097a.546.546 0 0 1-.177.732a.96.96 0 0 0-.436.802v.034a.96.96 0 0 0 .436.802a.546.546 0 0 1 .177.732l-.056.097a.546.546 0 0 1-.722.213a.96.96 0 0 0-.913.023l-.029.017a.96.96 0 0 0-.476.779a.546.546 0 0 1-.546.519h-.112a.546.546 0 0 1-.546-.519a.96.96 0 0 0-.476-.779l-.029-.017a.96.96 0 0 0-.913-.023a.546.546 0 0 1-.722-.213l-.056-.097a.546.546 0 0 1 .177-.732a.96.96 0 0 0 .436-.802v-.034a.96.96 0 0 0-.436-.802a.546.546 0 0 1-.177-.732l.056-.097a.546.546 0 0 1 .722-.213a.96.96 0 0 0 .913-.023l.029-.017a.96.96 0 0 0 .476-.779");
}

.guvqp3f2r {
  d: path("M7.125 4.5h9.75A2.625 2.625 0 0 1 19.5 7.125v5.75a2.625 2.625 0 0 1-2.625 2.625h-9.75A2.625 2.625 0 0 1 4.5 12.875v-5.75A2.625 2.625 0 0 1 7.125 4.5M2.5 18.5h19");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
