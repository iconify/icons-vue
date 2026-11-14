<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ofew06fen"/><path class="t5w7vcqxx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:delivery-card-left" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ofew06fen {
  d: path("M7.625 2.5h8.75A2.625 2.625 0 0 1 19 5.125v13.75a2.625 2.625 0 0 1-2.625 2.625h-8.75A2.625 2.625 0 0 1 5 18.875V5.125A2.625 2.625 0 0 1 7.625 2.5M2.5 21.5h19");
}

.t5w7vcqxx {
  d: path("m9.768 6.918l3.424-.727a1.5 1.5 0 0 1 1.779 1.155l.416 1.956a1.5 1.5 0 0 1-1.155 1.78l-3.424.727a1.5 1.5 0 0 1-1.779-1.155l-.416-1.956a1.5 1.5 0 0 1 1.155-1.78M15.75 15.5h.01");
}

</style>
