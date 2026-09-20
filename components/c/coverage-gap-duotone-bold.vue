<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c1kziyotx"/><path class="hieqhxiaw"/><path class="kdztqobrs"/><path class="hifrecvqa"/><path class="gv6xijbrb"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="pty_wsbvs"/><path class="s2pzwwb8y"/><path class="s4_6dccau"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:coverage-gap-duotone-bold" /></template>
<style>
.c1kziyotx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d6cu3qpew {
  d: path("M17 3h4v18h-4");
}

.gv6xijbrb {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m13.5 12.5 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hieqhxiaw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 3h4v18h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hifrecvqa {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m10.5 12.5 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kdztqobrs {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 9h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ldodvk1_f {
  d: path("M7 3H3v18h4");
}

.pty_wsbvs {
  d: path("M8 9h8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s2pzwwb8y {
  d: path("m10.5 12.5 3 3");
}

.s4_6dccau {
  d: path("m13.5 12.5 -3 3");
}

</style>
