<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ywzofukdy"/><path class="x-6ru0kwl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:delivery-room" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x-6ru0kwl {
  d: path("M17.5 14.75c.25-1 1.5-1.25 2-.5");
}

.ywzofukdy {
  d: path("M5 21.5v-17c0-1.1.9-2 2-2h8c1.1 0 2 .9 2 2v6.881M14 12.5h.01m.49 5.75a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm2.25 0h.01m2.49 0h.01");
}

</style>
