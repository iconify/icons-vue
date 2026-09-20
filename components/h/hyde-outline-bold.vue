<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="crp-16bgl"/><path class="yomctlb4k"/><path class="n7epx7dso"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hyde-outline-bold" /></template>
<style>
.crp-16bgl {
  d: path("M14 3h5a3 3 0 0 1 3 3v8a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V6a3 3 0 0 1 3 -3h5");
}

.n7epx7dso {
  d: path("M13.5 6.5 16 9l-4 4 -4 -4 2.5 -2.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.yomctlb4k {
  d: path("M7 17v4l4 -4");
}

</style>
