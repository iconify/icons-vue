<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t1n1s_mtk"/><path class="e3tmhtu7v"/><path class="nce43obfj"/><path class="lqmu-cc7k"/><path class="ukiwwmbbr"/><path class="ilryez4rq"/><path class="qi3wr9i3q"/><path class="m3p-trbfr"/><path class="uvtjmqbif"/><path class="o58i3acrw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chord-duotone-regular" /></template>
<style>
.e3tmhtu7v {
  fill: currentColor;
  d: path("M8 13a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ilryez4rq {
  d: path("M8 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.lqmu-cc7k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 18V4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m3p-trbfr {
  d: path("M8 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.nce43obfj {
  fill: currentColor;
  d: path("M8 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o58i3acrw {
  d: path("M12 4h5");
}

.qi3wr9i3q {
  d: path("M8 13a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.t1n1s_mtk {
  fill: currentColor;
  d: path("M8 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ukiwwmbbr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 4h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uvtjmqbif {
  d: path("M12 18V4");
}

</style>
