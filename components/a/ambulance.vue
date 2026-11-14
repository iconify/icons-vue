<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cokkw2b6a"/><path class="v3eu-jbor"/><path class="wm4qj7bzi"/><path class="r1zcajz8u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ambulance" /></template>
<style>
.cokkw2b6a {
  d: path("M3.5 19V9c0-1.5 1-2.5 2.5-2.5h12c1.5 0 2.5 1 2.5 2.5v10Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r1zcajz8u {
  fill: currentColor;
  d: path("M5.75 19h.5a1.25 1.25 0 0 1 1.25 1.25a1.25 1.25 0 0 1-1.25 1.25h-.5a1.25 1.25 0 0 1-1.25-1.25A1.25 1.25 0 0 1 5.75 19m12 0h.5a1.25 1.25 0 0 1 1.25 1.25a1.25 1.25 0 0 1-1.25 1.25h-.5a1.25 1.25 0 0 1-1.25-1.25A1.25 1.25 0 0 1 17.75 19");
}

.v3eu-jbor {
  fill: currentColor;
  d: path("M10.75 3h2.5a1.25 1.25 0 0 1 1.25 1.25a1.25 1.25 0 0 1-1.25 1.25h-2.5A1.25 1.25 0 0 1 9.5 4.25A1.25 1.25 0 0 1 10.75 3");
}

.wm4qj7bzi {
  d: path("M7.83 8.75h8.34a1.5 1.5 0 0 1 1.471 1.794l-.15.75A1.5 1.5 0 0 1 16.02 12.5H7.98a1.5 1.5 0 0 1-1.471-1.206l-.15-.75A1.5 1.5 0 0 1 7.83 8.75m-2.08 7a1 1 0 1 0 2 0a1 1 0 1 0-2 0m10.5 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0M12 14.25v3.25m-1.5-1.75h3");
}

</style>
