<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="x6e_qy8ax"/><path class="vq9pneb-v"/><path class="zey5ebc0a"/><path class="x0tldbb7w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:black-hole-duotone-bold" /></template>
<style>
.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vq9pneb-v {
  fill: currentColor;
  d: path("M2 12a10 2.5 0 1 1 20 0 10 2.5 0 1 1 -20 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.x0tldbb7w {
  d: path("M2 12a10 2.5 0 1 1 20 0 10 2.5 0 1 1 -20 0");
}

.x6e_qy8ax {
  fill: currentColor;
  d: path("M7 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zey5ebc0a {
  d: path("M7 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

</style>
