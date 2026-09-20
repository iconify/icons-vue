<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hzisptbze"/><path class="je9gsi5id"/><path class="todxtrbsg"/><path class="rl2nbiksm"/><path class="og9kjwb4a"/><path class="p3ptowbul"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:layer-down-duotone-bold" /></template>
<style>
.hzisptbze {
  fill: currentColor;
  d: path("M4 4.5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.je9gsi5id {
  fill: currentColor;
  d: path("M4 11.5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.og9kjwb4a {
  d: path("M12 15.5V20");
}

.p3ptowbul {
  d: path("M9.5 19.5 12 22l2.5 -2.5");
}

.rl2nbiksm {
  d: path("M4 11.5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.todxtrbsg {
  d: path("M4 4.5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2");
}

</style>
