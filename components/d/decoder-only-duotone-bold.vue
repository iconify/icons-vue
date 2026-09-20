<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hx3h6oiex"/><path class="axwkrzbmo"/><path class="nuz6-76is"/><path class="zl61012kd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:decoder-only-duotone-bold" /></template>
<style>
.axwkrzbmo {
  d: path("m8 8 4 4 -4 4 -4 -4Z");
}

.hx3h6oiex {
  fill: currentColor;
  d: path("m8 8 4 4 -4 4 -4 -4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nuz6-76is {
  d: path("M15 12h6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.zl61012kd {
  d: path("M18.5 9.5 21 12l-2.5 2.5");
}

</style>
