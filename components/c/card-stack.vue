<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gip75k0_s"/><path class="i_9q_l4kr"/><path class="b7ia6pnpc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:card-stack" /></template>
<style>
.b7ia6pnpc {
  d: path("M8.5 8V6.5A1.5 1.5 0 0 1 10 5h10a1.5 1.5 0 0 1 1.5 1.5v6A1.5 1.5 0 0 1 20 14h-1.5");
}

.gip75k0_s {
  d: path("M5.125 11h7.75a2.625 2.625 0 0 1 2.625 2.625v3.75A2.625 2.625 0 0 1 12.875 20h-7.75A2.625 2.625 0 0 1 2.5 17.375v-3.75A2.625 2.625 0 0 1 5.125 11M2.5 14h13");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i_9q_l4kr {
  d: path("M5.5 11V9.5A1.5 1.5 0 0 1 7 8h10a1.5 1.5 0 0 1 1.5 1.5V17h-3");
}

</style>
