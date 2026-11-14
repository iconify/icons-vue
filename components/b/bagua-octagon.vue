<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qxei5st8u"/><path class="ja8_zg6om"/><path class="qz1eedcwb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bagua-octagon" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ja8_zg6om {
  d: path("M6.5 12a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0");
}

.qxei5st8u {
  d: path("M9.121 2.5h5.758a1.5 1.5 0 0 1 1.06.439l5.122 5.122a1.5 1.5 0 0 1 .439 1.06v5.758a1.5 1.5 0 0 1-.439 1.06l-5.122 5.122a1.5 1.5 0 0 1-1.06.439H9.121a1.5 1.5 0 0 1-1.06-.439l-5.122-5.122a1.5 1.5 0 0 1-.439-1.06V9.121a1.5 1.5 0 0 1 .439-1.06l5.122-5.122a1.5 1.5 0 0 1 1.06-.439");
}

.qz1eedcwb {
  d: path("M12 6.5a2.75 2.75 0 0 1 0 5.5a2.75 2.75 0 0 0 0 5.5m0-8.25h.01m-.01 5.5h.01");
}

</style>
