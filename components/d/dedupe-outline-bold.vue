<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="s0mwfjblf"/><path class="t1v31abzy"/><path class="mc77_dknm"/><path class="ghtf55bhy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dedupe-outline-bold" /></template>
<style>
.ghtf55bhy {
  d: path("m19 10 -4 4");
}

.mc77_dknm {
  d: path("m15 10 4 4");
}

.s0mwfjblf {
  d: path("M2 9a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t1v31abzy {
  d: path("M13 9a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

</style>
