<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="pq_ccfr1s"/><path class="g-4ao_sjh"/><path class="vwkc5abrd"/><path class="pwgc9ejdf"/><path class="z3v4a-b3b"/><path class="he2cqebcu"/><path class="tdc4xtbqn"/><path class="vzsad0b2k"/><path class="qaaffjxln"/><path class="vijdpmg8r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:forward-proxy-duotone-bold" /></template>
<style>
.g-4ao_sjh {
  fill: currentColor;
  d: path("M2 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.he2cqebcu {
  d: path("M2 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.pq_ccfr1s {
  fill: currentColor;
  d: path("M2 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.pwgc9ejdf {
  fill: currentColor;
  d: path("M15 10a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.qaaffjxln {
  d: path("M10 12h5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tdc4xtbqn {
  d: path("M2 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.vijdpmg8r {
  d: path("M15 10a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

.vwkc5abrd {
  fill: currentColor;
  d: path("M2 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.vzsad0b2k {
  d: path("m4 6 6 6 -6 6");
}

.z3v4a-b3b {
  d: path("M2 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
