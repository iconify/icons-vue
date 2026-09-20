<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hq2ofvbyd"/><path class="ik_7mybce"/><path class="naudy1b1k"/><path class="x67_elb1a"/><path class="ef5tcc6_c"/><path class="me6k632rv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:luggage-tag-duotone-bold" /></template>
<style>
.ef5tcc6_c {
  d: path("M4 16h14");
}

.hq2ofvbyd {
  fill: currentColor;
  d: path("M6 4h10l4 4 -4 4H6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ik_7mybce {
  fill: currentColor;
  d: path("M8 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.me6k632rv {
  d: path("M4 20h10");
}

.naudy1b1k {
  d: path("M6 4h10l4 4 -4 4H6Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.x67_elb1a {
  d: path("M8 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
