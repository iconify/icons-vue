<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yv03hfb3v"/><path class="xp1fowqsf"/><circle class="pwhosj3ug"/><path class="s30-xwbda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:devinfo" /></template>
<style>
.pwhosj3ug {
  cx: 35.524px;
  cy: 11.974px;
  r: 0.75px;
  fill: currentColor;
}

.s30-xwbda {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.524 14.55v5.795");
}

.xp1fowqsf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.48 19.818a6.345 6.345 0 1 1 11.385-3.852a6.345 6.345 0 0 1-9.278 5.626l-3.534 1.325z");
}

.yv03hfb3v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.565 22.238v17.57a2.687 2.687 0 0 1-2.693 2.692h-16.24a2.687 2.687 0 0 1-2.693-2.693l-.003-31.614A2.687 2.687 0 0 1 15.63 5.5h16.243a2.687 2.687 0 0 1 2.692 2.693v1.5M17.973 37.55l10.927-.057");
}

</style>
