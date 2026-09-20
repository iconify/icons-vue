<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="elo9fvbju"/><path class="t1ic5ob8h"/><path class="eb35pyb6t"/><path class="xvr6s5efs"/><path class="zwghjjvbs"/><path class="azskw1rof"/><path class="fbyngunlt"/><path class="bie4u9bix"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:greedy-duotone-thin" /></template>
<style>
.azskw1rof {
  d: path("m9 16 5 -5");
}

.bie4u9bix {
  d: path("M19 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.eb35pyb6t {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 16h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.elo9fvbju {
  fill: currentColor;
  d: path("M14 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.fbyngunlt {
  d: path("M14 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t1ic5ob8h {
  fill: currentColor;
  d: path("M19 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.xvr6s5efs {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 16 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zwghjjvbs {
  d: path("M2 16h7");
}

</style>
