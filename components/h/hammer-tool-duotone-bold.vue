<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="a8qz153ka"/><path class="w4onmpb6s"/><path class="zuwyzt6-u"/><path class="v8xtwkb5y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hammer-tool-duotone-bold" /></template>
<style>
.a8qz153ka {
  fill: currentColor;
  d: path("M10 6h7v4h-7Z");
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

.v8xtwkb5y {
  d: path("M10 6c-2 1 -3 3 -3 4");
}

.w4onmpb6s {
  d: path("M10 6h7v4h-7Z");
}

.zuwyzt6-u {
  d: path("M13 10v12");
}

</style>
