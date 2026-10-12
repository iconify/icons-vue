<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="yjt4258yu"/><path class="nv9on9jjz"/><path class="mxbn55-eo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:file-image" /></template>
<style>
.mxbn55-eo {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.25 11.5h.01");
}

.nv9on9jjz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.75 2.75v3.5a2 2 0 0 0 2 2h3.5m-11 9.5l2.75-3.5l2.25 2.5l1.25-1.25l1.75 2.25");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yjt4258yu {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.75 2.75h-6.5a2.5 2.5 0 0 0-2.5 2.5v13.5a2.5 2.5 0 0 0 2.5 2.5h9.5a2.5 2.5 0 0 0 2.5-2.5V8.25Z");
}

</style>
