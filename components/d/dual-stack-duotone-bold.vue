<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="o2gn1ccwm"/><path class="mgc5w0bas"/><path class="nfsra8bqu"/><path class="x43bekb2j"/><path class="n-g2uz0bh"/><path class="zwghjjvbs"/><path class="gt7coxqxq"/><path class="gvmht2kii"/><path class="ifhv18rgk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dual-stack-duotone-bold" /></template>
<style>
.gt7coxqxq {
  d: path("M3 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.gvmht2kii {
  d: path("M3 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.ifhv18rgk {
  d: path("M12 12h6");
}

.mgc5w0bas {
  fill: currentColor;
  d: path("M3 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.n-g2uz0bh {
  d: path("M2 8h7");
}

.nfsra8bqu {
  fill: currentColor;
  d: path("M3 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.o2gn1ccwm {
  fill: currentColor;
  d: path("M9 10a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2h-8a2 2 0 0 1 -2 -2Z");
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

.x43bekb2j {
  d: path("M9 10a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2h-8a2 2 0 0 1 -2 -2Z");
}

.zwghjjvbs {
  d: path("M2 16h7");
}

</style>
