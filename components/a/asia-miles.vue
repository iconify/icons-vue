<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="dqvyd7ykg"/><ellipse class="yabqozb2m"/></g><path class="hl6aibb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:asia-miles" /></template>
<style>
.dqvyd7ykg {
  d: path("m7.934 43l10.587-24.176L29.164 43");
}

.hl6aibb3i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.048 5s1.83 14.521 13.018 11.083c-3.388 2.608-7.198 4.64-11.893 5.462");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yabqozb2m {
  cx: 18.549px;
  cy: 30.912px;
  rx: 9.988px;
  ry: 2.01px;
}

</style>
