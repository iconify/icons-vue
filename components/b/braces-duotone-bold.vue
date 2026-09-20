<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="in9c_7bsd"/><path class="cd7j3zbyn"/><path class="j-uhg7vsc"/><path class="m44kqpqtt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:braces-duotone-bold" /></template>
<style>
.cd7j3zbyn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 3h3v7l2 2 -2 2v7h-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.in9c_7bsd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11 3H8v7l-2 2 2 2v7h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j-uhg7vsc {
  d: path("M11 3H8v7l-2 2 2 2v7h3");
}

.m44kqpqtt {
  d: path("M13 3h3v7l2 2 -2 2v7h-3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
