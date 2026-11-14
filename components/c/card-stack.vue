<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f3fz2-h9x"/><path class="i_9q_l4kr"/><path class="b7ia6pnpc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:card-stack" /></template>
<style>
.b7ia6pnpc {
  d: path("M8.5 8V6.5A1.5 1.5 0 0 1 10 5h10a1.5 1.5 0 0 1 1.5 1.5v6A1.5 1.5 0 0 1 20 14h-1.5");
}

.f3fz2-h9x {
  d: path("M2.5 11h13v9h-13Zm0 3h13");
}

.i_9q_l4kr {
  d: path("M5.5 11V9.5A1.5 1.5 0 0 1 7 8h10a1.5 1.5 0 0 1 1.5 1.5V17h-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
