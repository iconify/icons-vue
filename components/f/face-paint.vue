<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b09u5l-mq"/><path class="i4mvzwbzw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:face-paint" /></template>
<style>
.b09u5l-mq {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0m6.25-4h.01m6.49 0h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i4mvzwbzw {
  d: path("m15.625 12l.024.064A1.44 1.44 0 0 0 17 13a.414.414 0 0 1 .293.707l-.192.192a1.5 1.5 0 0 0-.395 1.425l.044.176a.38.38 0 0 1-.589.401l-.039-.028a1.5 1.5 0 0 0-1.744 0l-.039.028a.38.38 0 0 1-.589-.401l.044-.176a1.5 1.5 0 0 0-.395-1.425l-.192-.192A.414.414 0 0 1 13.5 13a1.44 1.44 0 0 0 1.351-.936l.024-.064a.401.401 0 0 1 .75 0");
}

</style>
