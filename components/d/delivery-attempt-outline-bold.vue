<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="g00uv-b-x"/><path class="koh8ckbdb"/><path class="k2mg4f2ls"/><path class="wno0-e7zg"/><path class="n7lv6gb1d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:delivery-attempt-outline-bold" /></template>
<style>
.g00uv-b-x {
  d: path("M4 5h9a2 2 0 0 1 2 2v3h3.5l2.5 2.5V15a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2");
}

.k2mg4f2ls {
  d: path("M15 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.koh8ckbdb {
  d: path("M5 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.n7lv6gb1d {
  d: path("M7.5 14.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wno0-e7zg {
  d: path("M8.5 8v4");
}

</style>
