<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ilryez4rq"/><path class="qi3wr9i3q"/><path class="m3p-trbfr"/><path class="uvtjmqbif"/><path class="o58i3acrw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chord-outline-bold" /></template>
<style>
.ilryez4rq {
  d: path("M8 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.m3p-trbfr {
  d: path("M8 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.o58i3acrw {
  d: path("M12 4h5");
}

.qi3wr9i3q {
  d: path("M8 13a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uvtjmqbif {
  d: path("M12 18V4");
}

</style>
