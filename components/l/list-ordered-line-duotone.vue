<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vo6pq_eni"/><path class="qe311mboy"/><path class="b7flqff0r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-ordered-line-duotone" /></template>
<style>
.b7flqff0r {
  stroke-linejoin: round;
  d: path("M5.13477 15.0549C5.13477 14.4723 5.56616 14 6.0983 14C6.63045 14 7.06184 14.4723 7.06184 15.0549C7.06184 15.6375 6.8515 15.9177 6.47963 16.4326L5.13477 18H7.06184");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qe311mboy {
  stroke-linejoin: round;
  d: path("M5.13477 7.5136L7.06207 6V10");
}

.vo6pq_eni {
  d: path("M21 6H13M21 10H13M21 14H13M21 18H13");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
