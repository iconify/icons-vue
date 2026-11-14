<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u04gbnbho"/><path class="rhh_egbxt"/><path class="id1aw0lsj"/><path class="a23xryq3y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dialogue-flow" /></template>
<style>
.a23xryq3y {
  d: path("M16.25 5.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.id1aw0lsj {
  d: path("M9.5 12.5h9V7.75");
}

.rhh_egbxt {
  d: path("M9.5 9.5v8h3");
}

.u04gbnbho {
  d: path("M4.5 2.5h6a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2h-4l-2.5 2v-2a2 2 0 0 1-1.5-2v-3a2 2 0 0 1 2-2m10 12.75h5a2 2 0 0 1 2 2v4.25L19 20h-4.5a2 2 0 0 1-2-2v-.75a2 2 0 0 1 2-2");
}

</style>
