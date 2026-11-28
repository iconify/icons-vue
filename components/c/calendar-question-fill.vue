<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jfe5w5buu"/><path class="ju8y-lfzl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:calendar-question-fill" /></template>
<style>
.jfe5w5buu {
  d: path("M11 21H6C4.34315 21 3 19.6569 3 18V8C3 6.34315 4.34315 5 6 5H18C19.6569 5 21 6.34315 21 8V9M7 11H13M8 3V7M16 3V7M16.4 14.6C16.4 13.7164 17.1164 13 18 13C18.8836 13 19.6 13.7164 19.6 14.6C19.6 15.2459 19.2116 15.8285 18.6154 16.0769C18.2427 16.2322 18 16.5963 18 17");
}

.ju8y-lfzl {
  fill: currentColor;
  d: path("M19 21C19 21.5523 18.5523 22 18 22C17.4477 22 17 21.5523 17 21C17 20.4477 17.4477 20 18 20C18.5523 20 19 20.4477 19 21Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
