<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="x43bekb2j"/><path class="n-g2uz0bh"/><path class="zwghjjvbs"/><path class="gt7coxqxq"/><path class="gvmht2kii"/><path class="ifhv18rgk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dual-stack-outline-bold" /></template>
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

.n-g2uz0bh {
  d: path("M2 8h7");
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
