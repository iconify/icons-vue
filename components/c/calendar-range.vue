<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ebcu1lbmd"/><path class="n0-__2-aa"/><path class="tz7pjxbkb"/><path class="tt0znloqm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:calendar-range" /></template>
<style>
.ebcu1lbmd {
  d: path("M7 4.5h10A3.5 3.5 0 0 1 20.5 8v9.5A3.5 3.5 0 0 1 17 21H7a3.5 3.5 0 0 1-3.5-3.5V8A3.5 3.5 0 0 1 7 4.5m1-2v4m8-4v4m-12.5 3h17");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n0-__2-aa {
  fill: currentColor;
  d: path("M6.25 15.25a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

.tt0znloqm {
  fill: currentColor;
  d: path("M15.75 15.25a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

.tz7pjxbkb {
  d: path("M7.25 15.25h9.5");
}

</style>
