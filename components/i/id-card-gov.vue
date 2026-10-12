<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="q0_gb6qzx"/><rect class="o2r00obxl"/><path class="jj_ulgv8n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:id-card-gov" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jj_ulgv8n {
  d: path("m16.14 8.32l.41.91q.14.32.49.36l.99.1q.35.04.09.27l-.75.67q-.26.23-.18.57l.21.98q.07.34-.23.17l-.87-.5q-.3-.18-.6 0l-.87.5q-.3.17-.23-.17l.21-.98q.08-.34-.18-.57l-.75-.67q-.26-.23.09-.27l.99-.1q.35-.04.49-.36l.41-.91q.14-.32.28 0m-2.39 6.93h4.5");
}

.o2r00obxl {
  width: 5px;
  height: 7.5px;
  x: 5.75px;
  y: 8.25px;
  rx: 1px;
}

.q0_gb6qzx {
  width: 18.5px;
  height: 13.5px;
  x: 2.75px;
  y: 5.25px;
  rx: 2px;
}

</style>
