<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tx8yyac3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-clock-corner" /></template>
<style>
.tx8yyac3v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 21H6a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v2M8 3v2m8-2v2M4 9h16m-9 8a5 5 0 1 0 10 0a5 5 0 0 0-10 0m5-2v2h2");
}

</style>
