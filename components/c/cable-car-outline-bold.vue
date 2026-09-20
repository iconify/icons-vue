<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c7dgfu7wx"/><path class="d1zyr9bfc"/><path class="lvnmieb7r"/><path class="y07a50u1t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cable-car-outline-bold" /></template>
<style>
.c7dgfu7wx {
  d: path("M2 4h20");
}

.d1zyr9bfc {
  d: path("M12 4v4");
}

.lvnmieb7r {
  d: path("M5 10a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.y07a50u1t {
  d: path("M5 13h14");
}

</style>
