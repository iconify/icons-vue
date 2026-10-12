<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bbph0vbkh"/><path class="v8cap8bet"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:eye-gaze" /></template>
<style>
.bbph0vbkh {
  d: path("M2.75 10c1.65-3.5 4.6-5.75 8-5.75s6.35 2.25 8 5.75c-1.65 3.5-4.6 5.75-8 5.75S4.4 13.5 2.75 10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v8cap8bet {
  d: path("M8.25 10a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m6.46 3.45l6.08 2.6q.46.2 0 .39l-2.08.87q-.46.19-.64.66l-.89 2.31q-.18.47-.35 0l-2.41-6.56q-.17-.47.29-.27");
}

</style>
