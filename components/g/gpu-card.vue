<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="igqs9mbjo"/><rect class="ozjmdnbgd"/><circle class="pgksv8bwe"/><path class="qffcw0b3k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gpu-card" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.igqs9mbjo {
  d: path("M2.75 4.75v14.5");
}

.ozjmdnbgd {
  width: 15.5px;
  height: 10.5px;
  x: 5.75px;
  y: 5.75px;
  rx: 2px;
}

.pgksv8bwe {
  cx: 10.25px;
  cy: 11px;
  r: 2px;
}

.qffcw0b3k {
  d: path("M16.75 9a2 2 0 1 1 0 4a2 2 0 1 1 0-4m-8 7.25v3h7v-3");
}

</style>
