<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zk_4bjb4m"/><path class="esh17sbch"/><path class="vhf3_kexp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bathroom-sink-outline-bold" /></template>
<style>
.esh17sbch {
  d: path("M7 12V7h3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vhf3_kexp {
  d: path("M12 16v5");
}

.zk_4bjb4m {
  d: path("M4 12h16a10 10 0 0 1 -16 0");
}

</style>
