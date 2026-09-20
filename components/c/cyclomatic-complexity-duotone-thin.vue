<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hd7idxb2m"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="b_x7v_t0t"/><path class="bx3fv3b8c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cyclomatic-complexity-duotone-thin" /></template>
<style>
.b_x7v_t0t {
  d: path("m12 7 3 3 -3 3 -3 -3Z");
}

.bx3fv3b8c {
  d: path("M12 13v4");
}

.d6cu3qpew {
  d: path("M17 3h4v18h-4");
}

.hd7idxb2m {
  fill: currentColor;
  d: path("m12 7 3 3 -3 3 -3 -3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ldodvk1_f {
  d: path("M7 3H3v18h4");
}

</style>
