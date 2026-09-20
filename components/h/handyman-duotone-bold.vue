<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="y4l98q7pn"/><path class="n6_6pyqbf"/><path class="k74vnib1e"/><path class="fqjewfbna"/><path class="bkx9mvb8q"/><path class="c744qo9dt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:handyman-duotone-bold" /></template>
<style>
.bkx9mvb8q {
  d: path("M14 20v-7h8v7Z");
}

.c744qo9dt {
  d: path("M16 13v-3h4v3");
}

.fqjewfbna {
  d: path("M2 16a4 4 0 0 1 8 0");
}

.k74vnib1e {
  d: path("M3 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.n6_6pyqbf {
  fill: currentColor;
  d: path("M14 20v-7h8v7Z");
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

.y4l98q7pn {
  fill: currentColor;
  d: path("M3 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
