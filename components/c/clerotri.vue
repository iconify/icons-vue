<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9gr6p07l"/><path class="fjfdj-r3x"/><path class="t8ge91b7x"/><path class="iw98d-bug"/><path class="he84y511n"/><circle class="te-uxrbrk"/><path class="g2wj9jbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:clerotri" /></template>
<style>
.fjfdj-r3x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.02 10.23c-.5 2-4.193 6.201-4.943 8.451M38.55 20.73c-1.748 1.094-4.674 5.905-6.582 7.314");
}

.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.he84y511n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.03 37.77c1.58-1.324 7.037-2.552 8.966-3.932");
}

.i9gr6p07l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.453 20.73c2.057.143 7.252-2.03 9.624-2.048M9.523 20.74c1.748 1.094 4.602 5.904 6.51 7.313M24 10.16c.5 2 4.172 6.27 4.922 8.52");
}

.iw98d-bug {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.93 37.79c-.771-1.912-.253-7.481-.969-9.743M15.01 37.83c.771-1.912.31-7.525 1.026-9.786");
}

.t8ge91b7x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.49 20.77c-2.057.143-7.193-2.071-9.565-2.089M32.99 37.84c-1.58-1.324-7.061-2.62-8.99-4");
}

.te-uxrbrk {
  cx: 24px;
  cy: 25px;
  r: 5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
