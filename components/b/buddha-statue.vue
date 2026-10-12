<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u1w-djb2c"/><circle class="b36niz7vv"/><path class="b6q-3bces"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:buddha-statue" /></template>
<style>
.b36niz7vv {
  cx: 12px;
  cy: 7.75px;
  r: 2.25px;
}

.b6q-3bces {
  d: path("M12 12.5c2.25 0 3.75 1.25 4.25 3.25l.4 1.75c2 .25 3.6 1.5 3.85 3l.25.75H3.25l.25-.75c.25-1.5 1.85-2.75 3.85-3l.4-1.75c.5-2 2-3.25 4.25-3.25m-2.5 6h5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u1w-djb2c {
  d: path("M6.75 8a5.25 5.25 0 1 1 10.5 0");
}

</style>
