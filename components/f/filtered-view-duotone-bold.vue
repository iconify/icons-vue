<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="itsd58b9q"/><path class="adtk031os"/><path class="jgpu15buw"/><path class="ozi-k-boi"/><path class="prs91gbcd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:filtered-view-duotone-bold" /></template>
<style>
.adtk031os {
  fill: currentColor;
  d: path("M7 10h10l-3.5 3.5v5h-3v-5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.itsd58b9q {
  fill: currentColor;
  d: path("M3 4.5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v15a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.jgpu15buw {
  d: path("M3 4.5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v15a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.ozi-k-boi {
  d: path("M3 7h18");
}

.prs91gbcd {
  d: path("M7 10h10l-3.5 3.5v5h-3v-5Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
