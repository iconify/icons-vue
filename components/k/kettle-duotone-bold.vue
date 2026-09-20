<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="j7cn4_bey"/><path class="g-qvc03sc"/><path class="q3ca84baq"/><path class="iv9vhg42o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:kettle-duotone-bold" /></template>
<style>
.g-qvc03sc {
  d: path("M6 10h10v8a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

.iv9vhg42o {
  d: path("M7 10c0 -5 8 -5 8 0");
}

.j7cn4_bey {
  fill: currentColor;
  d: path("M6 10h10v8a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.q3ca84baq {
  d: path("m16 11 4 -4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
