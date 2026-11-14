<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j2di41bqy"/><path class="b35r_sbpr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bank-swift-code" /></template>
<style>
.b35r_sbpr {
  d: path("M15 8.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m2.25-1c1.25-3 4.25-4.5 4-2.5c-.25 1.5-2 2.25-4 2.5m-8.125 4.5l.71-.546a1.5 1.5 0 0 1 1.83 0l.71.546A.697.697 0 0 1 11.95 13h-2.4a.697.697 0 0 1-.425-1.25M8.75 13v3.25m4-3.25v3.25m-5.25 0H14");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j2di41bqy {
  d: path("m13.521 5.137l3.191.168a2.625 2.625 0 0 1 2.483 2.483l.168 3.191a2.63 2.63 0 0 1-.765 1.994l-6.51 6.51a2.625 2.625 0 0 1-3.712 0l-3.359-3.359a2.625 2.625 0 0 1 0-3.712l6.51-6.51a2.63 2.63 0 0 1 1.994-.765");
}

</style>
