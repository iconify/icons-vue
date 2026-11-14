<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vk8e85z8c"/><path class="kl5zaqi3r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:blast-schedule" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kl5zaqi3r {
  d: path("m14.625 15.625l-.006.002A.928.928 0 0 0 14.125 17l.032.052a.315.315 0 0 1-.407.448l-.045-.022a.96.96 0 0 0-1.33.522a.401.401 0 0 1-.75 0a.96.96 0 0 0-1.33-.522l-.045.022a.315.315 0 0 1-.407-.448L9.875 17a.928.928 0 0 0-.494-1.373l-.006-.002a.395.395 0 0 1 0-.75l.006-.002a.928.928 0 0 0 .494-1.373l-.032-.052A.315.315 0 0 1 10.25 13l.045.022a.96.96 0 0 0 1.33-.522a.401.401 0 0 1 .75 0a.96.96 0 0 0 1.33.522L13.75 13a.315.315 0 0 1 .407.448l-.032.052a.928.928 0 0 0 .494 1.373l.006.002a.395.395 0 0 1 0 .75");
}

.vk8e85z8c {
  d: path("M6.5 4h11A3.5 3.5 0 0 1 21 7.5V18a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 18V7.5A3.5 3.5 0 0 1 6.5 4M3 8.5h18m-13-6v3m8-3v3");
}

</style>
