<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kvrb2m1qz"/><path class="tuz1ao15a"/><path class="xslfg2evh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:clay-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kvrb2m1qz {
  fill: currentColor;
  d: path("M4 14C4 8 8 4 12 4c5 0 8 5 8 9s-3 5 -8 5 -8 0 -8 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.tuz1ao15a {
  d: path("M4 14C4 8 8 4 12 4c5 0 8 5 8 9s-3 5 -8 5 -8 0 -8 -4");
}

.xslfg2evh {
  d: path("M6 21h12");
}

</style>
