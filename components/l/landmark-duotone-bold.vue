<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="o17dzpf1f"/><path class="d4v3t3bns"/><path class="g91uwsb-i"/><path class="mjsa21byd"/><path class="ok9ioqb8x"/><path class="cjsg0ab2y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:landmark-duotone-bold" /></template>
<style>
.cjsg0ab2y {
  d: path("M2 20h20");
}

.d4v3t3bns {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 17h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g91uwsb-i {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 20h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mjsa21byd {
  d: path("M8 17V7l4 -4 4 4v10");
}

.o17dzpf1f {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 17V7l4 -4 4 4v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ok9ioqb8x {
  d: path("M4 17h16");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
