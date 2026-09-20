<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zwjmk5b0j"/><path class="n7t0anb5n"/><path class="z3eyrdd0c"/><path class="vrecxx6kh"/><path class="jlfjgzbqx"/><path class="y6kfzfgng"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:locker-duotone-bold" /></template>
<style>
.jlfjgzbqx {
  d: path("M9 9h6");
}

.n7t0anb5n {
  fill: currentColor;
  d: path("M14 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
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

.vrecxx6kh {
  d: path("M9 6h6");
}

.y6kfzfgng {
  d: path("M14 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.z3eyrdd0c {
  d: path("M6 4a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

.zwjmk5b0j {
  fill: currentColor;
  d: path("M6 4a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
