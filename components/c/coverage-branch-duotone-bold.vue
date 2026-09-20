<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c1kziyotx"/><path class="hieqhxiaw"/><path class="nuplvwbls"/><path class="nyaq4j2gw"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="e8t0a9beq"/><path class="zn6_kf4ff"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:coverage-branch-duotone-bold" /></template>
<style>
.c1kziyotx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d6cu3qpew {
  d: path("M17 3h4v18h-4");
}

.e8t0a9beq {
  d: path("M12 7v4l-4 4");
}

.hieqhxiaw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 3h4v18h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ldodvk1_f {
  d: path("M7 3H3v18h4");
}

.nuplvwbls {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 7v4l-4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nyaq4j2gw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m12 11 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.zn6_kf4ff {
  d: path("m12 11 4 4");
}

</style>
