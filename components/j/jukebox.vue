<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rb2i7tb5q"/><path class="qa_yjoe3f"/><circle class="sapxmnb0l"/><path class="q2ubtvbpa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:jukebox" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q2ubtvbpa {
  d: path("M9 16v1.75M12 16v1.75M15 16v1.75M7.5 19.5v1.75m9-1.75v1.75");
}

.qa_yjoe3f {
  d: path("M7.5 14v-4a4.5 4.5 0 0 1 9 0v4");
}

.rb2i7tb5q {
  d: path("M4.75 10a7.25 7.25 0 0 1 14.5 0v7.5a2 2 0 0 1-2 2H6.75a2 2 0 0 1-2-2Z");
}

.sapxmnb0l {
  cx: 12px;
  cy: 10.5px;
  r: 2px;
}

</style>
