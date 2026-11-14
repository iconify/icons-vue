<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ev1njzc4c"/><path class="p61a4n9fp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:life-child-plan" /></template>
<style>
.ev1njzc4c {
  d: path("M4 14.5c0-3.5 3.5-6 8-6s8 2.5 8 6c0 2.25-1.25 4-3.5 5V22H14v-1.75c-.75.25-1.25.25-2 .25s-1.25 0-2-.25V22H7.5v-2.5c-2.25-1-3.5-2.75-3.5-5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p61a4n9fp {
  d: path("M4.5 13h-2v3h2M8.914 4.183l2.368-1.291a1.5 1.5 0 0 1 1.436 0l2.368 1.291a1.5 1.5 0 0 1 0 2.634l-2.368 1.291a1.5 1.5 0 0 1-1.436 0L8.914 6.817a1.5 1.5 0 0 1 0-2.634M7.75 13.25h.01");
}

</style>
