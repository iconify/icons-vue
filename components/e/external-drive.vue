<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="kvmhc8qvq"/><path class="xt_-p1bsc"/><path class="o1zlll-zk"/><path class="l84lpzbjr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:external-drive" /></template>
<style>
.kvmhc8qvq {
  width: 12.5px;
  height: 14px;
  x: 5.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.l84lpzbjr {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 16.75v2.5a2 2 0 0 0 2 2h5.25");
}

.o1zlll-zk {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 13.25h.01");
}

.xt_-p1bsc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 6.5h5.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
