<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bvum7wbdx"/><path class="qd48qvart"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:adjustable-wrench" /></template>
<style>
.bvum7wbdx {
  d: path("M16.419 2.984za1.75 1.75 0 0 1 0 2.475l-.53.531a1.5 1.5 0 0 0 0 2.121l.177.177a1.25 1.25 0 0 0 1.768 0a1.25 1.25 0 0 1 1.767 0l.177.176a1.5 1.5 0 0 1 0 2.122l-2.234 2.233a1.75 1.75 0 0 1-1.43.502l-1.736-.193a1.75 1.75 0 0 1-1.044-.501l-2.02-2.02a1.75 1.75 0 0 1-.479-.894l-.419-2.098a1.75 1.75 0 0 1 .478-1.581l3.051-3.05a1.75 1.75 0 0 1 2.474 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qd48qvart {
  d: path("M12.354 11.646za2 2 0 0 1 0 2.829l-4.243 4.243a2 2 0 0 1-2.829 0a2 2 0 0 1 0-2.829l4.243-4.243a2 2 0 0 1 2.829 0m3.005-.883l2.121 2.121");
}

</style>
