<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="agzn98nil"/><path class="aw18wcbea"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:blood-vessel" /></template>
<style>
.agzn98nil {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 8.5c4 0 6-2 9.25-2s5.25 2 9.25 2m-18.5 7c4 0 6-2 9.25-2s5.25 2 9.25 2");
}

.aw18wcbea {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 12h.01M12 10h.01m5.49 2h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
