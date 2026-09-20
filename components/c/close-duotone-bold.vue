<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="l5kcxbbsq"/><path class="m7voa5bvi"/><path class="edg0x3nuq"/><path class="wvha8hh3o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:close-duotone-bold" /></template>
<style>
.edg0x3nuq {
  d: path("m5 5 14 14");
}

.l5kcxbbsq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m5 5 14 14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m7voa5bvi {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19 5 5 19");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wvha8hh3o {
  d: path("M19 5 5 19");
}

</style>
