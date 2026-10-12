<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="s_eh1sbpu"/><path class="mgedwabdu"/><path class="o6a500beq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chart-line-markers" /></template>
<style>
.mgedwabdu {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.75 17.25l5.25-3L15 16l5-4.5m-8-8.75A3.25 3.25 0 0 0 8.75 6c0 2.25 3.25 4.75 3.25 4.75s3.25-2.5 3.25-4.75A3.25 3.25 0 0 0 12 2.75");
}

.o6a500beq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 6h.01");
}

.s_eh1sbpu {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 3.75v14.5a2 2 0 0 0 2 2h14.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
