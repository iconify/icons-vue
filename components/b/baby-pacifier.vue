<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="l02idcpke"/><path class="oq_o2gw7k"/><circle class="har4go24q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:baby-pacifier" /></template>
<style>
.har4go24q {
  cx: 12px;
  cy: 18.75px;
  r: 2.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l02idcpke {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 8V4.75a1.5 1.5 0 0 1 3 0V8M7.25 8h9.5a3.5 3.5 0 0 1 0 7c-2 0-3.25-.75-4.75-1.75c-1.5 1-2.75 1.75-4.75 1.75a3.5 3.5 0 0 1 0-7");
}

.oq_o2gw7k {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.25 11.5h.01m9.49 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
