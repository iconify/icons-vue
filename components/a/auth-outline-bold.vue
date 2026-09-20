<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xfv57rbcs"/><path class="w_otj1bev"/><path class="hubgvrbhc"/><path class="plag3bb8h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:auth-outline-bold" /></template>
<style>
.hubgvrbhc {
  d: path("M2 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.plag3bb8h {
  d: path("M6.5 14H13");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.w_otj1bev {
  d: path("M12 9a4 4 0 0 1 8 0");
}

.xfv57rbcs {
  d: path("M10 11a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2h-8a2 2 0 0 1 -2 -2Z");
}

</style>
