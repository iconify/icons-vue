<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lyqq45kxt"/><path class="l7dxj4nrm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:breadboard-wires" /></template>
<style>
.l7dxj4nrm {
  d: path("M12 11c0-8 5-8 5 0M7 11h.01M12 11h.01M17 11h.01M7 14h.01M12 14h.01M17 14h.01M7 17h.01M12 17h.01M17 17h.01");
}

.lyqq45kxt {
  d: path("M2.5 8h19v12h-19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
