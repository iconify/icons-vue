<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j_q_y1bdx"/><path class="cbn_tbceq"/><path class="ew9xmvlqg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-line-down" /></template>
<style>
.cbn_tbceq {
  d: path("m7 7l3.5 4l3-2l6 7");
}

.ew9xmvlqg {
  d: path("M15.5 16h4v-4");
}

.j_q_y1bdx {
  d: path("M3.5 3.5v17h17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
