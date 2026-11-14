<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sp1gx7bfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:group-settings" /></template>
<style>
.sp1gx7bfp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20c0-2.5 2.1-4.25 4.75-4.25S12 17.5 12 20c0 .6-.4 1-1 1H3.5c-.6 0-1-.4-1-1M4 9.75a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0M13 6a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m.25 6.5c.65-.75 1.45-1.25 2.25-1.25c1.75 0 3.25.5 4.25 1.25m-2.352 2.82za.546.546 0 0 1 .546-.519h.112a.546.546 0 0 1 .546.519a.96.96 0 0 0 .476.779l.029.017a.96.96 0 0 0 .913.023a.546.546 0 0 1 .722.213l.056.097a.546.546 0 0 1-.177.732a.96.96 0 0 0-.436.802v.034a.96.96 0 0 0 .436.802a.546.546 0 0 1 .177.732l-.056.097a.546.546 0 0 1-.722.213a.96.96 0 0 0-.913.023l-.029.017a.96.96 0 0 0-.476.779a.546.546 0 0 1-.546.519h-.112a.546.546 0 0 1-.546-.519a.96.96 0 0 0-.476-.779l-.029-.017a.96.96 0 0 0-.913-.023a.546.546 0 0 1-.722-.213l-.056-.097a.546.546 0 0 1 .177-.732a.96.96 0 0 0 .436-.802v-.034a.96.96 0 0 0-.436-.802a.546.546 0 0 1-.177-.732l.056-.097a.546.546 0 0 1 .722-.213a.96.96 0 0 0 .913-.023l.029-.017a.96.96 0 0 0 .476-.779");
}

</style>
