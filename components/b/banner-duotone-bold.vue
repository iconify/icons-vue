<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hr6yi9b8a"/><path class="cyp_qzb7b"/><path class="viv5gg8xx"/><path class="e9t3fjbay"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:banner-duotone-bold" /></template>
<style>
.cyp_qzb7b {
  fill: currentColor;
  d: path("M5 7.5A2.5 2.5 0 0 1 7.5 5h9A2.5 2.5 0 0 1 19 7.5a2.5 2.5 0 0 1 -2.5 2.5h-9A2.5 2.5 0 0 1 5 7.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.e9t3fjbay {
  d: path("M5 7.5A2.5 2.5 0 0 1 7.5 5h9A2.5 2.5 0 0 1 19 7.5a2.5 2.5 0 0 1 -2.5 2.5h-9A2.5 2.5 0 0 1 5 7.5");
}

.hr6yi9b8a {
  fill: currentColor;
  d: path("M2 4a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.viv5gg8xx {
  d: path("M2 4a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
