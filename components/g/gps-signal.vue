<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s01pi9bwp"/><path class="jjdlwtbqn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gps-signal" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jjdlwtbqn {
  d: path("M10.75 12.25a1.75 1.75 0 1 1-3.5 0a1.75 1.75 0 1 1 3.5 0M15 2.75A6.25 6.25 0 0 1 21.25 9M15 6.25A2.75 2.75 0 0 1 17.75 9");
}

.s01pi9bwp {
  d: path("M9 21.25c-.3 0-.6-.12-.82-.33c-2.48-2.32-4.93-5.32-4.93-8.67a5.75 5.75 0 0 1 11.5 0c0 3.35-2.45 6.35-4.93 8.67c-.22.21-.52.33-.82.33");
}

</style>
