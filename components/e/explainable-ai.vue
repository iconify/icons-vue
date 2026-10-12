<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yyj3fzyxz"/><path class="qacx1tbuj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:explainable-ai" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qacx1tbuj {
  d: path("M12 8q.48 3.52 4 4q-3.52.48-4 4q-.48-3.52-4-4q3.52-.48 4-4");
}

.yyj3fzyxz {
  d: path("M2.9 11.6C5.1 7.45 8.3 5.25 12 5.25s6.9 2.2 9.1 6.35a.85.85 0 0 1 0 .8c-2.2 4.15-5.4 6.35-9.1 6.35s-6.9-2.2-9.1-6.35a.85.85 0 0 1 0-.8");
}

</style>
