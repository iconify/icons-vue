<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="i64ili29r"/><path class="ylu4kimdh"/><path class="ig71m4b4e"/><path class="s0tzl36gy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:harbour-outline-bold" /></template>
<style>
.i64ili29r {
  d: path("M10 4.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.ig71m4b4e {
  d: path("M7 8.5h10");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s0tzl36gy {
  d: path("M19 13a7 7 0 0 1 -14 0");
}

.ylu4kimdh {
  d: path("M12 6.5V20");
}

</style>
