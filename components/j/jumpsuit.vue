<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oezae9b3j"/><path class="isqo_9bcz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:jumpsuit" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.isqo_9bcz {
  d: path("M9.75 3L12 6.25L14.25 3m-7.5 9.25h10.5");
}

.oezae9b3j {
  d: path("M9.75 2.75h4.5q1 0 1.89.45l2.22 1.1q.89.45 1.25 1.38l1.28 3.39q.36.93-.61 1.15l-1.31.31q-.97.22-.99 1.22l-.21 8.5q-.02 1-1.02 1H15q-1 0-1.27-.96l-1.46-5.33q-.27-.96-.54 0l-1.46 5.33q-.27.96-1.27.96H7.25q-1 0-1.02-1l-.21-8.5q-.02-1-.99-1.22l-1.31-.31q-.97-.22-.61-1.15l1.28-3.39q.36-.93 1.25-1.38l2.22-1.1q.89-.45 1.89-.45");
}

</style>
