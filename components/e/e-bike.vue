<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f6i1cab1k"/><circle class="testxab1c"/><circle class="qispqfbwt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:e-bike" /></template>
<style>
.f6i1cab1k {
  d: path("M7.75 17.75h3L8.46 8M7 8h3m.75 9.75l2.96-5.21m1.48-2.61L16 8.5l2.04 6.85M16 8.5l-.82-2.75h-1.75m.53 6.36l.98-1.75q.25-.43-.19-.68l-.64-.36q-.44-.25-.69.18l-.98 1.75q-.25.43.19.68l.64.36q.44.25.69-.18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qispqfbwt {
  cx: 18.75px;
  cy: 17.75px;
  r: 2.5px;
}

.testxab1c {
  cx: 5.25px;
  cy: 17.75px;
  r: 2.5px;
}

</style>
