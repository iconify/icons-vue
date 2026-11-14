<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sx1odw0ad"/><path class="caot7zb4g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:deposit-goal-jar" /></template>
<style>
.caot7zb4g {
  d: path("M7.5 17.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-2.5-4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.sx1odw0ad {
  d: path("M6.5 5.5h11V8h-11ZM7 8h10c1.5 1.5 2 3 2 4.5V19a2.5 2.5 0 0 1-2.5 2.5h-9A2.5 2.5 0 0 1 5 19v-6.5c0-1.5.5-3 2-4.5Zm7.5-2.5V2m0 0l4 1.25l-4 1.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
