<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="phjvadcnz"/><path class="nd7y81b9b"/><circle class="v4wf3czoy"/><path class="k96j4-b7r"/><circle class="phidi_btw"/><path class="b3_k96hhs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:duet-split" /></template>
<style>
.b3_k96hhs {
  d: path("M14.1 16a2.5 2.5 0 0 1 5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k96j4-b7r {
  d: path("M4.9 16a2.5 2.5 0 0 1 5 0");
}

.nd7y81b9b {
  d: path("M12 3.75v16.5");
}

.phidi_btw {
  cx: 16.6px;
  cy: 10px;
  r: 1.75px;
}

.phjvadcnz {
  width: 18.5px;
  height: 16.5px;
  x: 2.75px;
  y: 3.75px;
  rx: 3px;
}

.v4wf3czoy {
  cx: 7.4px;
  cy: 10px;
  r: 1.75px;
}

</style>
