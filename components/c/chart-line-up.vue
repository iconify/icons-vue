<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j_q_y1bdx"/><path class="vq7iobc8q"/><path class="t35yxj0uh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-line-up" /></template>
<style>
.j_q_y1bdx {
  d: path("M3.5 3.5v17h17");
}

.t35yxj0uh {
  d: path("M15.5 7h4v4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vq7iobc8q {
  d: path("m7 16l3.5-4.5l3 2l6-6.5");
}

</style>
