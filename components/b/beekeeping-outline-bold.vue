<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="bkiaatbvd"/><path class="n75imzbwr"/><path class="jkuojibnm"/><path class="bih55pzif"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:beekeeping-outline-bold" /></template>
<style>
.bih55pzif {
  d: path("M11 3a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.bkiaatbvd {
  d: path("M5 5h14v4H5Z");
}

.jkuojibnm {
  d: path("M3 20h18");
}

.n75imzbwr {
  d: path("M5 12h14v4H5Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
