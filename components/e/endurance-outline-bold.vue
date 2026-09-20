<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="cmt-chbtl"/><path class="iwanrcb5f"/><path class="s97tcsbyl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:endurance-outline-bold" /></template>
<style>
.cmt-chbtl {
  d: path("m2 20 6 -6 3 3 4 -4 7 7");
}

.iwanrcb5f {
  d: path("M15 13V5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s97tcsbyl {
  d: path("M15 5h4v4h-4");
}

</style>
