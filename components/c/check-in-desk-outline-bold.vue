<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="j05_so5ho"/><path class="eh9_5accs"/><path class="znp47mbys"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:check-in-desk-outline-bold" /></template>
<style>
.eh9_5accs {
  d: path("M7 5a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H9a2 2 0 0 1 -2 -2Z");
}

.j05_so5ho {
  d: path("M3 16a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.znp47mbys {
  d: path("M6 17.5h12");
}

</style>
